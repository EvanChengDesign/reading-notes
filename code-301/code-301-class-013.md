# **Reading Notes | 10 APR 2024**

# Class 013  
  
## **Questions & Answers**  

### Which HTTP method would you use to update a record through an API?
The HTTP method used to update a record through an API is `PUT` for a complete update or `PATCH` for a partial update.

### Which REST methods require an ID parameter?
The REST methods that typically require an ID parameter are `GET` (when retrieving a specific resource), `PUT`, `PATCH`, and `DELETE`.

### What’s the relationship between REST and CRUD?
REST (Representational State Transfer) is a software architectural style that provides standards between computer systems on the web, making it easier to communicate. CRUD (Create, Read, Update, Delete) represents the four basic operations of persistent storage. The operations in CRUD correspond to the HTTP methods POST (Create), GET (Read), PUT/PATCH (Update), and DELETE (Delete), which are used in RESTful APIs to manage resources.

### If you had to describe the process of creating a RESTful API in 5 steps, what would they be?
1. **Define the data structure** and resources.
2. **Identify the API endpoints** that correspond to different operations on the resources.
3. **Choose the appropriate HTTP methods** (GET, POST, PUT, PATCH, DELETE) for these operations.
4. **Implement request handling** for each endpoint, ensuring idempotence where necessary.
5. **Test the API** to ensure it meets functional, performance, and security standards.
