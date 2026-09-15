# MongoDB — Complete Basic Notes

## 1. JSON and BSON

**JSON (JavaScript Object Notation)** represents data using key-value pairs, similar to a HashMap or Dictionary.

```json
{
  "name": "Shourya",
  "age": 20
}
```

JSON supports strings, numbers, booleans, arrays, objects, and `null`.

MongoDB stores documents internally as **BSON (Binary JSON)**. BSON also supports special types such as `ObjectId`, dates, and binary data. If `_id` is not provided, MongoDB generates a unique one automatically.

### Array

```json
{
  "name": "Shourya",
  "skills": ["Python", "MySQL"]
}
```

### Embedded object

```json
{
  "name": "Shourya",
  "address": {
    "city": "Jaipur",
    "pincode": 302021
  }
}
```

MongoDB uses a **flexible schema**, so documents in the same collection can contain different fields.

## 2. MongoDB Structure

```text
Atlas cluster
└── Database
    └── Collection
        └── Documents
```

For your work:

- Cluster: `atlas-104b3m-shard-0`
- Database: `PCEA24IT051`
- Collection: `students`

| MySQL | MongoDB |
|---|---|
| Database | Database |
| Table | Collection |
| Row | Document |
| Column | Field |
| SQL | MongoDB Query Language |
| Structured schema | Flexible schema |

## 3. Basic Database Commands

MongoDB commands can be executed in `mongosh`.

```javascript
// Show all accessible databases
show dbs

// Create or switch to a database
use PCEA24IT051

// Show collections in the current database
show collections

// Create a collection
db.createCollection("students")
```

A database is permanently created when data is stored in it.

## 4. Insert Documents

### Insert one document

```javascript
db.students.insertOne({
  rollNo: 101,
  name: "Vasanth",
  age: 21,
  department: "CSE",
  marks: 85,
  skills: ["Java", "Python", "MongoDB"],
  address: {
    city: "Chennai",
    state: "Tamil Nadu"
  },
  scholarship: true
})
```

### Insert multiple documents

```javascript
db.students.insertMany([
  { rollNo: 102, name: "Aman", department: "CSE", marks: 90 },
  { rollNo: 103, name: "Riya", department: "IT", marks: 82 }
])
```

## 5. Retrieve and Display Data

```javascript
// Display every document
db.students.find()

// Display every document neatly
db.students.find().pretty()

// Retrieve one document
db.students.findOne()

// Count all documents
db.students.countDocuments()

// Find all CSE students
db.students.find({ department: "CSE" })
```

### Display selected fields

```javascript
db.students.find(
  {},
  { name: 1, department: 1, marks: 1, _id: 0 }
)
```

Here, `1` includes a field and `0` excludes a field.

## 6. Comparison (Relational) Operators

| Operator | Meaning |
|---|---|
| `$lt` | Less than |
| `$gt` | Greater than |
| `$lte` | Less than or equal to |
| `$gte` | Greater than or equal to |
| `$eq` | Equal to |
| `$ne` | Not equal to |

```javascript
// Marks below 85
db.students.find({ marks: { $lt: 85 } })

// Marks above 85
db.students.find({ marks: { $gt: 85 } })

// Marks at most 85
db.students.find({ marks: { $lte: 85 } })

// Marks at least 85
db.students.find({ marks: { $gte: 85 } })

// Department equals CSE
db.students.find({ department: { $eq: "CSE" } })

// Simpler equality syntax
db.students.find({ department: "CSE" })

// Department is not CSE
db.students.find({ department: { $ne: "CSE" } })
```

### Range condition

Find students whose marks are between 70 and 90, including both values:

```javascript
db.students.find({
  marks: { $gte: 70, $lte: 90 }
})
```

## 7. Logical Operators

| Operator | Meaning |
|---|---|
| `$and` | All conditions must be true |
| `$or` | At least one condition must be true |
| `$nor` | None of the conditions should be true |
| `$not` | Reverses one field condition |

### `$and`

Find CSE students with marks greater than 85:

```javascript
db.students.find({
  $and: [
    { department: "CSE" },
    { marks: { $gt: 85 } }
  ]
})
```

MongoDB automatically applies AND between different fields, so this shorter query works too:

```javascript
db.students.find({
  department: "CSE",
  marks: { $gt: 85 }
})
```

### `$or`

Find students who are from CSE or have marks greater than 85:

```javascript
db.students.find({
  $or: [
    { department: "CSE" },
    { marks: { $gt: 85 } }
  ]
})
```

### `$nor`

Find students who are not from CSE and whose marks are not greater than 85:

```javascript
db.students.find({
  $nor: [
    { department: "CSE" },
    { marks: { $gt: 85 } }
  ]
})
```

### `$not`

Find students whose marks are not greater than 85:

```javascript
db.students.find({
  marks: { $not: { $gt: 85 } }
})
```

`$not` is applied to one field condition. `$and`, `$or`, and `$nor` accept arrays of conditions.

## 8. Array Operators

Suppose the document contains:

```javascript
skills: ["Java", "Python", "MongoDB"]
```

| Operator | Meaning |
|---|---|
| `$in` | Matches at least one listed value |
| `$nin` | Matches none of the listed values |
| `$all` | Matches every listed value |

### `$in` — any value

Find students who know Java or C++:

```javascript
db.students.find({
  skills: { $in: ["Java", "C++"] }
})
```

### `$nin` — none of the values

Find students who know neither Java nor Python:

```javascript
db.students.find({
  skills: { $nin: ["Java", "Python"] }
})
```

### `$all` — every value

Find students who know both Java and MongoDB:

```javascript
db.students.find({
  skills: { $all: ["Java", "MongoDB"] }
})
```

Important difference:

```javascript
// Java OR MongoDB
skills: { $in: ["Java", "MongoDB"] }

// Java AND MongoDB
skills: { $all: ["Java", "MongoDB"] }
```

Search for one value inside an array:

```javascript
db.students.find({ skills: "Java" })
```

## 9. Common Syntax Mistakes

Incorrect:

```javascript
db.students.find({{ department: "CSE" }, { marks: [$gt: 85] }})
```

Correct:

```javascript
db.students.find({
  department: "CSE",
  marks: { $gt: 85 }
})
```

Remember:

- Use `{ }` for objects and conditions.
- Use `[ ]` for arrays and lists of logical conditions.
- MongoDB operators begin with `$`.
- Separate fields with commas.
- Collection names, field names, and stored values are case-sensitive.
- Use the exact stored value: `"MongoDB"` is different from `"Mongo"`.

## 10. Quick Revision

```javascript
use PCEA24IT051
show collections
db.students.find().pretty()
db.students.find({ department: "CSE" })
db.students.find({ marks: { $gt: 85 } })
db.students.find({ department: "CSE", marks: { $gt: 85 } })
db.students.find({ skills: { $all: ["Java", "MongoDB"] } })
```

