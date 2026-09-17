|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> const categories = [
|     "Electronics",
|     "Mobiles",
|     "Laptops",
|     "Clothing",
|     "Books",
|     "Furniture",
|     "Shoes",
|     "Accessories",
|     "Home Appliances",
|     "Sports"
| ];
|
| const brands = [
|     "Apple",
|     "Samsung",
|     "Dell",
|     "HP",
|     "Lenovo",
|     "Sony",
|     "Nike",
|     "Adidas",
|     "Puma",
|     "OnePlus"
| ];
|
| const cities = [
|     "Chennai",
|     "Bangalore",
|     "Hyderabad",
|     "Coimbatore",
|     "Salem",
|     "Erode",
|     "Tiruchengode",
|     "Madurai",
|     "Trichy",
|     "Pondicherry"
| ];
|
| const tags = [
|     "new",
|     "popular",
|     "discount",
|     "premium",
|     "bestseller",
|     "trending",
|     "featured",
|     "budget"
| ];
|
| const paymentMethods = [
|     "UPI",
|     "Credit Card",
|     "Debit Card",
|     "Cash",
|     "Net Banking"
| ];
|
|
| // Array to temporarily store documents
| let products = [];
|
|
| // Generate 5000 documents
| for (let i = 1; i <= 5000; i++) {
|
|     let category = categories[i % categories.length];
|
|     let brand = brands[i % brands.length];
|
|     let city = cities[i % cities.length];
|
|     let price = Math.floor(Math.random() * 90000) + 1000;
|
|     let quantity = Math.floor(Math.random() * 10) + 1;
|
|     let rating = Number(
|         (Math.random() * 4 + 1).toFixed(1)
|     );
|
|
|     let productTags = [
|         tags[i % tags.length],
|         tags[(i + 2) % tags.length]
|     ];
|
|
|     let product = {
|
|         productId: i,
|
|         name: brand + " Product " + i,
|
|         category: category,
|
|         brand: brand,
|
|         price: price,
|
|         quantity: quantity,
|
|         rating: rating,
|
|         description:
|             "This is a high quality " +
|             category +
|             " product from " +
|             brand +
|             " with excellent features and performance.",
|
|         tags: productTags,
|
|
|         seller: {
|
|             sellerId: 1000 + (i % 100),
|
|             name: "Seller " + (i % 100),
|
|             city: city
|         },
|
|
|         location: {
|
|             type: "Point",
|
|             coordinates: [
|                 76.95 + (Math.random() * 0.5),
|                 11.00 + (Math.random() * 0.5)
|             ]
|         },
|         paymentMethods: paymentMethods,
|         isActive: i % 5 !== 0,
|         createdAt: new Date(
|             2024,
|             i % 12,
|             (i % 28) + 1
|         )
|     };
|     // Add email to some documents
|     // Useful for Sparse Index
|     if (i % 3 === 0) {
|
|         product.email =
|             "customer" + i + "@example.com";
|     }
|     // Add discount to some documents
|     // Useful for Partial Index
|     if (i % 4 === 0) {
|
|         product.discount =
|             Math.floor(Math.random() * 40) + 5;
|     }
|     // Add document to array
|     products.push(product);
|     // Insert in batches of 500
|     if (products.length === 500) {
|
|         db.product.insertMany(products);
|
|         products = [];
|     }
| }
| // Insert remaining documents
| if (products.length > 0) {
|
|     db.product.insertMany(products);
| }
| print("5000 documents inserted successfully!");
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> db.product.countDocuments()
5000
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> db.product.find({price: {$gt: 50000}}).explain("executionStats")
{
  explainVersion: '1',
  queryPlanner: {
    namespace: 'PCEA24IT058.product',
    parsedQuery: { price: { '$gt': 50000 } },
    indexFilterSet: false,
    queryHash: '8E1D451A',
    planCacheShapeHash: '8E1D451A',
    planCacheKey: 'D910EC32',
    optimizationTimeMillis: 0,
    maxIndexedOrSolutionsReached: false,
    maxIndexedAndSolutionsReached: false,
    maxScansToExplodeReached: false,
    prunedSimilarIndexes: false,
    winningPlan: {
      isCached: false,
      stage: 'COLLSCAN',
      filter: { price: { '$gt': 50000 } },
      direction: 'forward'
    },
    rejectedPlans: []
  },
  executionStats: {
    executionSuccess: true,
    nReturned: 2312,
    executionTimeMillis: 3,
    totalKeysExamined: 0,
    totalDocsExamined: 5000,
    executionStages: {
      isCached: false,
      stage: 'COLLSCAN',
      filter: { price: { '$gt': 50000 } },
      nReturned: 2312,
      executionTimeMillisEstimate: 4,
      works: 5001,
      advanced: 2312,
      needTime: 2688,
      needYield: 0,
      saveState: 0,
      restoreState: 0,
      isEOF: 1,
      direction: 'forward',
      docsExamined: 5000
    }
  },
  queryShapeHash: '3D7AC93A68F2F2EDB9AF04734FC161D7845C6B8169870D343499E6E006C25767',
  command: {
    find: 'product',
    filter: { price: { '$gt': 50000 } },
    '$db': 'PCEA24IT058'
  },
  serverInfo: {
    host: 'ac-28kwaq2-shard-00-01.u5gi0my.mongodb.net',
    port: 27017,
    version: '8.0.32',
    gitVersion: 'f9eb55a7cc900f33a722a5b32a0fdbf54385c749'
  },
  serverParameters: {
    internalQueryFacetBufferSizeBytes: 104857600,
    internalQueryFacetMaxOutputDocSizeBytes: 104857600,
    internalLookupStageIntermediateDocumentMaxSizeBytes: 16793600,
    internalDocumentSourceGroupMaxMemoryBytes: 104857600,
    internalQueryMaxBlockingSortMemoryUsageBytes: 33554432,
    internalQueryProhibitBlockingMergeOnMongoS: 0,
    internalQueryMaxAddToSetBytes: 104857600,
    internalDocumentSourceSetWindowFieldsMaxMemoryBytes: 104857600,
    internalQueryFrameworkControl: 'trySbeRestricted',
    internalQueryPlannerIgnoreIndexWithCollationForRegex: 1
  },
  ok: 1,
  '$clusterTime': {
    clusterTime: Timestamp({ t: 1789634183, i: 4 }),
price_1nature: {
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> db.product.find({price: {$$gt: 50000}}).explain("executionStats")
{
  explainVersion: '1',
  queryPlanner: {
    namespace: 'PCEA24IT058.product',
    parsedQuery: { price: { '$gt': 50000 } },
    indexFilterSet: false,
    queryHash: '8E1D451A',
    planCacheShapeHash: '8E1D451A',
    planCacheKey: 'F4407A58',
    optimizationTimeMillis: 0,
    maxIndexedOrSolutionsReached: false,
    maxIndexedAndSolutionsReached: false,
    maxScansToExplodeReached: false,
    prunedSimilarIndexes: false,
    winningPlan: {
      isCached: false,
      stage: 'FETCH',
      inputStage: {
        stage: 'IXSCAN',
        keyPattern: { price: 1 },
        indexName: 'price_1',
        isMultiKey: false,
        multiKeyPaths: { price: [] },
        isUnique: false,
        isSparse: false,
        isPartial: false,
        indexVersion: 2,
        direction: 'forward',
        indexBounds: { price: [ '(50000, inf.0]' ] }
      }
    },
    rejectedPlans: []
  },
  executionStats: {
    executionSuccess: true,
    nReturned: 2312,
    executionTimeMillis: 4,
    totalKeysExamined: 2312,
    totalDocsExamined: 2312,
    executionStages: {
      isCached: false,
      stage: 'FETCH',
      nReturned: 2312,
      executionTimeMillisEstimate: 2,
      works: 2313,
      advanced: 2312,
      needTime: 0,
      needYield: 0,
      saveState: 0,
      restoreState: 0,
      isEOF: 1,
      docsExamined: 2312,
      alreadyHasObj: 0,
      inputStage: {
        stage: 'IXSCAN',
        nReturned: 2312,
        executionTimeMillisEstimate: 1,
        works: 2313,
        advanced: 2312,
        needTime: 0,
        needYield: 0,
        saveState: 0,
        restoreState: 0,
        isEOF: 1,
        keyPattern: { price: 1 },
        indexName: 'price_1',
        isMultiKey: false,
        multiKeyPaths: { price: [] },
        isUnique: false,
        isSparse: false,
        isPartial: false,
        indexVersion: 2,
        direction: 'forward',
        indexBounds: { price: [ '(50000, inf.0]' ] },
        keysExamined: 2312,
        seeks: 1,
        dupsTested: 0,
        dupsDropped: 0
      }
    }
  },
  queryShapeHash: '3D7AC93A68F2F2EDB9AF04734FC161D7845C6B8169870D343499E6E006C25767',
  command: {
    find: 'product',
    filter: { price: { '$gt': 50000 } },
    '$db': 'PCEA24IT058'
  },
  serverInfo: {
    host: 'ac-28kwaq2-shard-00-01.u5gi0my.mongodb.net',
    port: 27017,
    version: '8.0.32',
    gitVersion: 'f9eb55a7cc900f33a722a5b32a0fdbf54385c749'
  },
  serverParameters: {
    internalQueryFacetBufferSizeBytes: 104857600,
    internalQueryFacetMaxOutputDocSizeBytes: 104857600,
    internalLookupStageIntermediateDocumentMaxSizeBytes: 16793600,
    internalDocumentSourceGroupMaxMemoryBytes: 104857600,
    internalQueryMaxBlockingSortMemoryUsageBytes: 33554432,
    internalQueryProhibitBlockingMergeOnMongoS: 0,
    internalQueryMaxAddToSetBytes: 104857600,
    internalDocumentSourceSetWindowFieldsMaxMemoryBytes: 104857600,
    internalQueryFrameworkControl: 'trySbeRestricted',
    internalQueryPlannerIgnoreIndexWithCollationForRegex: 1
  },
  ok: 1,
  '$clusterTime': {
    clusterTime: Timestamp({ t: 1789634196, i: 4 }),
    signature: {
      hash: Binary.createFromBase64('YkxkuenJNVlZBNtd1abLVVJaUfc=', 0),
      keyId: Long('7634928556237127691')
    }
  },
  operationTime: Timestamp({ t: 1789634196, i: 4 })
}
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> db.product.getIndexes()
[
  { v: 2, key: { _id: 1 }, name: '_id_' },
  { v: 2, key: { price: 1 }, name: 'price_1' }
]
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> db.product.dropIndex("price_1")
{
  nIndexesWas: 2,
  ok: 1,
  '$clusterTime': {
    clusterTime: Timestamp({ t: 1789634202, i: 3 }),
    signature: {
      hash: Binary.createFromBase64('5ynFDq1xryTuowfwNI6CUwEizx8=', 0),
      keyId: Long('7634928556237127691')
    }
  },
  operationTime: Timestamp({ t: 1789634202, i: 3 })
}
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> db.product.createIndex({
|     category: 1,
|     price: -1
| })
category_1_price_-1
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> db.product.getIndexes()
[
  { v: 2, key: { _id: 1 }, name: '_id_' },
  { v: 2, key: { category: 1, price: -1 }, name: 'category_1_price_-1' }
]
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> db.product.createIndex({
|     tags: 1
| })
tags_1
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058> db.product.find({
|     tags: "bestseller"
| }).explain("executionStats")
{
  explainVersion: '1',
  queryPlanner: {
    namespace: 'PCEA24IT058.product',
    parsedQuery: { tags: { '$eq': 'bestseller' } },
    indexFilterSet: false,
    queryHash: '6D042180',
    planCacheShapeHash: '6D042180',
    planCacheKey: 'EFC7AA33',
    optimizationTimeMillis: 0,
    maxIndexedOrSolutionsReached: false,
    maxIndexedAndSolutionsReached: false,
    maxScansToExplodeReached: false,
    prunedSimilarIndexes: false,
    winningPlan: {
      isCached: false,
      stage: 'FETCH',
      inputStage: {
        stage: 'IXSCAN',
        keyPattern: { tags: 1 },
        indexName: 'tags_1',
        isMultiKey: true,
        multiKeyPaths: { tags: [ 'tags' ] },
        isUnique: false,
        isSparse: false,
        isPartial: false,
        indexVersion: 2,
        direction: 'forward',
        indexBounds: { tags: [ '["bestseller", "bestseller"]' ] }
      }
    },
    rejectedPlans: []
  },
  executionStats: {
    executionSuccess: true,
    nReturned: 1250,
    executionTimeMillis: 3,
    totalKeysExamined: 1250,
    totalDocsExamined: 1250,
    executionStages: {
      isCached: false,
      stage: 'FETCH',
      nReturned: 1250,
      executionTimeMillisEstimate: 2,
      works: 1251,
      advanced: 1250,
      needTime: 0,
      needYield: 0,
      saveState: 0,
      restoreState: 0,
      isEOF: 1,
      docsExamined: 1250,
      alreadyHasObj: 0,
      inputStage: {
        stage: 'IXSCAN',
        nReturned: 1250,
        executionTimeMillisEstimate: 0,
        works: 1251,
        advanced: 1250,
        needTime: 0,
        needYield: 0,
        saveState: 0,
        restoreState: 0,
        isEOF: 1,
        keyPattern: { tags: 1 },
        indexName: 'tags_1',
        isMultiKey: true,
        multiKeyPaths: { tags: [ 'tags' ] },
        isUnique: false,
        isSparse: false,
        isPartial: false,
        indexVersion: 2,
        direction: 'forward',
        indexBounds: { tags: [ '["bestseller", "bestseller"]' ] },
        keysExamined: 1250,
        seeks: 1,
        dupsTested: 1250,
        dupsDropped: 0
      }
    }
  },
  queryShapeHash: '4A04368F0A78AF13327816726BD9434C606A9F5DE554FB9EF0607897BE7826FD',
  command: {
    find: 'product',
    filter: { tags: 'bestseller' },
    '$db': 'PCEA24IT058'
  },
  serverInfo: {
    host: 'ac-28kwaq2-shard-00-01.u5gi0my.mongodb.net',
    port: 27017,
    version: '8.0.32',
    gitVersion: 'f9eb55a7cc900f33a722a5b32a0fdbf54385c749'
  },
  serverParameters: {
    internalQueryFacetBufferSizeBytes: 104857600,
    internalQueryFacetMaxOutputDocSizeBytes: 104857600,
    internalLookupStageIntermediateDocumentMaxSizeBytes: 16793600,
    internalDocumentSourceGroupMaxMemoryBytes: 104857600,
    internalQueryMaxBlockingSortMemoryUsageBytes: 33554432,
    internalQueryProhibitBlockingMergeOnMongoS: 0,
    internalQueryMaxAddToSetBytes: 104857600,
    internalDocumentSourceSetWindowFieldsMaxMemoryBytes: 104857600,
    internalQueryFrameworkControl: 'trySbeRestricted',
    internalQueryPlannerIgnoreIndexWithCollationForRegex: 1
  },
  ok: 1,
  '$clusterTime': {
    clusterTime: Timestamp({ t: 1789634215, i: 1 }),
    signature: {
      hash: Binary.createFromBase64('i6MTnaw8nqDRvxlrx/PO/irBkjw=', 0),
      keyId: Long('7634928556237127691')
    }
  },
  operationTime: Timestamp({ t: 1789634215, i: 1 })
}
Atlas atlas-104b3m-shard-0 [primary] PCEA24IT058>