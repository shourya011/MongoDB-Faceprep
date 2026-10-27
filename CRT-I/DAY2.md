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




# MongoDB — CRUD and Update Operations

## 1. CRUD Meaning

CRUD represents the four basic database operations:

| Operation | Meaning | MongoDB methods |
|---|---|---|
| Create | Add documents | `insertOne()`, `insertMany()` |
| Read | Retrieve documents | `findOne()`, `find()` |
| Update | Modify documents | `updateOne()`, `updateMany()` |
| Delete | Remove documents | `deleteOne()`, `deleteMany()` |

## 2. Sample Products Dataset

The following loop inserts 50 documents into the `products` collection:

```javascript
for (let i = 1; i <= 50; i++) {
  db.products.insertOne({
    productId: i,
    productName: "Product " + i,

    category:
      i % 5 === 0 ? "Laptop" :
      i % 5 === 1 ? "Mobile" :
      i % 5 === 2 ? "Headphones" :
      i % 5 === 3 ? "Keyboard" :
                      "Mouse",

    brand:
      i % 3 === 0 ? "Dell" :
      i % 3 === 1 ? "Samsung" :
                    "HP",

    price: 1000 + (i * 500),
    stock: 10 + i,
    rating: 3 + ((i % 3) * 0.5),
    inStock: i % 4 !== 0,

    tags: [
      "electronics",
      i % 2 === 0 ? "featured" : "new"
    ],

    seller: {
      sellerId: 1000 + i,
      sellerName: "Seller " + i
    },

    createdAt: new Date()
  });
}
```

Check the inserted data:

```javascript
db.products.find().pretty()
db.products.countDocuments()
```

## 3. Create Operations

### `insertOne()`

Inserts one document:

```javascript
db.products.insertOne({
  productId: 51,
  productName: "Product 51",
  category: "Mobile",
  brand: "Samsung",
  price: 26500,
  stock: 20,
  rating: 4.5,
  inStock: true,
  tags: ["electronics", "new"]
})
```

### `insertMany()`

Inserts multiple documents:

```javascript
db.products.insertMany([
  {
    productId: 52,
    productName: "Product 52",
    category: "Laptop",
    price: 40000
  },
  {
    productId: 53,
    productName: "Product 53",
    category: "Mouse",
    price: 1500
  }
])
```

## 4. Read Operations

### Display all documents

```javascript
db.products.find().pretty()
```

### Find one document

```javascript
db.products.findOne({ productId: 1 })
```

### Find all laptops

```javascript
db.products.find({ category: "Laptop" })
```

### Find products costing more than 10,000

```javascript
db.products.find({
  price: { $gt: 10000 }
})
```

### Display selected fields

```javascript
db.products.find(
  {},
  { productId: 1, productName: 1, price: 1, _id: 0 }
)
```

## 5. Update Methods

MongoDB update methods follow this structure:

```javascript
db.collection.updateOne(filter, update)
db.collection.updateMany(filter, update)
```

- `filter` selects the document or documents.
- `update` describes the changes.

### `updateOne()`

Updates only the first matching document:

```javascript
db.products.updateOne(
  { productId: 1 },
  { $set: { price: 2000 } }
)
```

### `updateMany()`

Updates every matching document:

```javascript
db.products.updateMany(
  { category: "Laptop" },
  { $set: { inStock: true } }
)
```

## 6. Update Operators

### `$set` — Set or replace a field

Changes an existing field or creates it if it does not exist:

```javascript
db.products.updateOne(
  { productId: 1 },
  {
    $set: {
      price: 1800,
      inStock: true
    }
  }
)
```

Update an embedded field using dot notation:

```javascript
db.products.updateOne(
  { productId: 1 },
  { $set: { "seller.sellerName": "Shourya Store" } }
)
```

### `$inc` — Increase or decrease a number

Increase stock by 5:

```javascript
db.products.updateOne(
  { productId: 1 },
  { $inc: { stock: 5 } }
)
```

Decrease stock by 2:

```javascript
db.products.updateOne(
  { productId: 1 },
  { $inc: { stock: -2 } }
)
```

Increase the prices of all Dell products by 500:

```javascript
db.products.updateMany(
  { brand: "Dell" },
  { $inc: { price: 500 } }
)
```

### `$push` — Add a value to an array

Adds a value even if it already exists:

```javascript
db.products.updateOne(
  { productId: 1 },
  { $push: { tags: "sale" } }
)
```

Add multiple values using `$each`:

```javascript
db.products.updateOne(
  { productId: 1 },
  {
    $push: {
      tags: { $each: ["popular", "discounted"] }
    }
  }
)
```

### `$addToSet` — Add only a unique array value

Adds `featured` only if it is not already present:

```javascript
db.products.updateOne(
  { productId: 1 },
  { $addToSet: { tags: "featured" } }
)
```

Add multiple unique values:

```javascript
db.products.updateOne(
  { productId: 1 },
  {
    $addToSet: {
      tags: { $each: ["sale", "popular"] }
    }
  }
)
```

Difference:

| Operator | Behaviour |
|---|---|
| `$push` | Adds the value even if it creates a duplicate |
| `$addToSet` | Adds the value only when it is not already present |

### `$unset` — Remove a field

The correct operator is **`$unset`**, not `$unsex`.

Remove `rating` from one product:

```javascript
db.products.updateOne(
  { productId: 1 },
  { $unset: { rating: "" } }
)
```

Remove `seller` from all Mouse products:

```javascript
db.products.updateMany(
  { category: "Mouse" },
  { $unset: { seller: "" } }
)
```

The value written after the field in `$unset` is ignored. An empty string is commonly used.

## 7. Using Multiple Update Operators Together

```javascript
db.products.updateOne(
  { productId: 5 },
  {
    $set: { inStock: true },
    $inc: { stock: 10 },
    $addToSet: { tags: "restocked" },
    $unset: { rating: "" }
  }
)
```

This query:

- Sets `inStock` to `true`.
- Increases `stock` by 10.
- Adds the unique tag `restocked`.
- Removes the `rating` field.

## 8. Delete Operations

### `deleteOne()`

Deletes only the first matching document:

```javascript
db.products.deleteOne({ productId: 1 })
```

### `deleteMany()`

Deletes every matching document:

```javascript
db.products.deleteMany({ category: "Mouse" })
```

Delete all out-of-stock products:

```javascript
db.products.deleteMany({ inStock: false })
```

### Delete every document

```javascript
db.products.deleteMany({})
```

> **Warning:** An empty filter `{}` matches every document. Use it carefully.

## 9. Verify Operations

After updating or deleting, check the affected data:

```javascript
db.products.findOne({ productId: 1 })
db.products.find({ category: "Laptop" }).pretty()
db.products.countDocuments()
```

An update result may look like:

```javascript
{
  acknowledged: true,
  matchedCount: 1,
  modifiedCount: 1
}
```

- `matchedCount` tells how many documents matched the filter.
- `modifiedCount` tells how many documents were actually changed.

A delete result may look like:

```javascript
{
  acknowledged: true,
  deletedCount: 1
}
```

## 10. Quick CRUD Revision

```javascript
// CREATE
db.products.insertOne({ productId: 51, productName: "Product 51" })

// READ
db.products.find({ category: "Laptop" })

// UPDATE ONE
db.products.updateOne(
  { productId: 1 },
  { $set: { price: 2000 } }
)

// UPDATE MANY
db.products.updateMany(
  { brand: "Dell" },
  { $inc: { price: 500 } }
)

// DELETE ONE
db.products.deleteOne({ productId: 51 })

// DELETE MANY
db.products.deleteMany({ inStock: false })
```

## 11. Important Safety Rules

- Check matching documents with `find()` before running `updateMany()` or `deleteMany()`.
- Never use `deleteMany({})` unless you intentionally want to remove every document.
- MongoDB collection names and field names are case-sensitive.
- Use `$addToSet` when duplicate array values should be prevented.
- Use negative values with `$inc` to decrease a number.
