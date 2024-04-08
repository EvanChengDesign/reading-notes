# **Reading Notes | 08 APR 2024**

# Class 011

### *Bookmarks:*
[Mongoose api](https://mongoosejs.com/docs/api.html#Model)

[React Router](https://reactrouter.com/en/6.20.1/router-components/browser-router)  
  

## **Questions & Answers**  
## Differences Between SQL and NoSQL Databases

| Feature | SQL | NoSQL |
|---------|-----|-------|
| **Base** | Table-based | Document, key-value, graph, or wide-column store |
| **Schema** | Fixed schema | Dynamic schema |
| **Scalability** | Vertically scalable | Horizontally scalable |
| **Transactions** | ACID compliant (Atomicity, Consistency, Isolation, Durability) | CAP theorem (Consistency, Availability, Partition tolerance) |
| **Query Language** | SQL (Structured Query Language) | Varies (e.g., NoSQL query language, JavaScript, etc.) |

---  

**What kind of data is a good fit for an SQL database?**  
Structured data with complex queries and transactions.

**Give a real world example.**  
A banking system that requires complex transactions and reporting.

**What kind of data is a good fit for a NoSQL database?**  
Unstructured or semi-structured data, requiring flexibility and scalability.

**Give a real world example.**  
Social media analytics involving large volumes of varied data types.

**Which type of database is best for hierarchical data storage?**  
NoSQL databases, especially document-based ones like MongoDB.

**Which type of database is best for scalability?**  
NoSQL databases due to their horizontal scalability.

**What does SQL stand for?**  
Structured Query Language.

**What is a relational database?**  
A database that stores and provides access to data points that are related to one another.

**What type of structure does a relational database work with?**  
Tables.

**What is a ‘schema’?**  
A structure that defines the organization of data in a database.

**What is a NoSQL database?**  
A database that provides a mechanism for storage and retrieval of data modeled in means other than the tabular relations used in relational databases.

**How does it work?**  
It works with various data models including document, key-value, wide-column, and graph formats.

**What is inside of a MongoDB database?**  
Collections of documents, which are sets of key-value pairs.

**Which is more flexible - SQL or MongoDB? and why.**  
MongoDB, because it allows for a dynamic schema that can evolve over time without the need to pre-define it.

**What is the disadvantage of a NoSQL database?**  
Less mature, with fewer transaction capabilities compared to SQL databases, making consistency a challenge in certain scenarios.
