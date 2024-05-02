 **Reading Notes | 2 MAY 2024**

# Class 004

### *Bookmarks:*

[sequelize api](https://sequelize.org/master/)

## **Questions & Answers**  

## Database Questions and Answers

### What type of database is the best fit for a complex query intensive environment?
**Answer:** A **relational database (SQL)** is the best fit for environments that require complex query processing. They are designed to handle a large volume of data and support complex queries efficiently.

### What type of database is the best fit for hierarchical data storage?
**Answer:** A **NoSQL database**, specifically **document-oriented databases** like MongoDB, are well-suited for hierarchical data storage. They can store nested data structures more naturally than relational databases.

### Describe the differences in scalability between a SQL and NoSQL database to a non-technical friend.
**Answer:** Imagine you have a closet for your clothes (SQL database) and a whole room to throw your clothes around (NoSQL database). The closet is great for organizing, but if you buy lots more clothes, you might run out of space or it gets hard to manage. The room (NoSQL), however, lets you keep adding more clothes easily without worrying too much about space or strict organization.

### Among data tables, what is a one-to-many relationship and how do we “relate” them?
**Answer:** A **one-to-many relationship** occurs when a record in one table can be associated with multiple records in another table. We relate them using a **foreign key** in the 'many' table that references the **primary key** of the 'one' table.

### Prior to designing your relational database, it might be useful to ___ a ___ of the database tables and their relationships.
**Answer:** Prior to designing your relational database, it might be useful to **create a diagram** of the database tables and their relationships.

### Explain the difference between a primary and foreign key.
**Answer:** A **primary key** is a unique identifier for each record in a database table, ensuring that no two rows have the same primary key. A **foreign key**, on the other hand, is a column in one table that links to the primary key of another table, allowing the tables to be related.

### How do we treat keywords and parameters differently in SQL syntax?
**Answer:** In SQL, **keywords** (like SELECT, FROM, WHERE) are predefined words that the database understands as commands, while **parameters** are values provided by the user that SQL uses to filter, update, or manipulate data based on the commands.

### Define normalization within the context of schemas and data.
**Answer:** **Normalization** is the process of organizing data in a database efficiently by eliminating redundancy and ensuring data dependencies make sense. It involves dividing large tables into smaller, less redundant tables and defining relationships between them.

### Explain the difference between one-to-one, one-to-many, and many-to-many relationships to a non-technical recruiter.
**Answer:** Imagine your personal relationships: a **one-to-one** relationship is like having one best friend; a **one-to-many** relationship is like you being a manager to several employees; and a **many-to-many** relationship is like a group of friends where everyone can be friends with everyone else.
