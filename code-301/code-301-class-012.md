# **Reading Notes | 09 APR 2024**

# Class 012

## **Questions & Answers**  
## HTTP Status Codes Explained

- **100’s** = Informational responses, indicating that the request has been received and the process is continuing.
- **200’s** = Success codes, meaning the request was successfully received, understood, and accepted.
- **300’s** = Redirection codes, indicating that further action needs to be taken by the client to complete the request.
- **400’s** = Client error codes, signifying that there was a problem with the request.
- **500’s** = Server error codes, indicating that the server failed to fulfill an apparently valid request.

## Specific Status Codes

- **What is a status code 202?**  
A 202 status code means "Accepted," indicating that the request has been accepted for processing, but the processing has not been completed.
- **What is a status code 308?**  
A 308 status code means "Permanent Redirect," signaling that the resource has been moved to the URL given by the Location headers.
- **What code would you use if an update didn’t return data to a client?**  
You would use 204 "No Content" when an update operation completes successfully but returns no content.
- **What code would you use if a resource used to exist but no longer does?**  
You would use 410 "Gone" to indicate that the resource is no longer available and will not be available again.
- **What is the ‘Forbidden’ status code?**  
The 'Forbidden' status code is 403, indicating that the server understands the request but refuses to authorize it.

## Development Practices and Definitions

- **Why do we need to pull our MongoDB database string out of our server and put it into our .env?**  
To enhance security and flexibility, allowing the database connection string to remain confidential and easily changeable without modifying the codebase.
- **What is middleware?**  
Middleware is software that lies between an operating system and the applications running on it, essentially functioning as a hidden translation layer.
- **What does app.use(express.json()) do?**  
It enables the express app to parse JSON bodies, allowing it to understand and process JSON requests.
- **What does the /:id mean in a route?**  
The /:id is a route parameter that represents a variable part of a URL, used to capture and pass a specific value (like an ID) to the route handler.
- **What is the difference between PUT and PATCH?**  
PUT replaces an entire resource, while PATCH partially updates an existing resource.
- **How do you make a default value in a schema?**  
In a schema, you define a default value by specifying it in the schema definition for a field, using the `default` keyword.
- **What does a 500 error status code mean?**  
A 500 error status code means "Internal Server Error," indicating that the server encountered an unexpected condition that prevented it from fulfilling the request.
- **What is the difference between a status 200 and a status 201?**  
Status 200 means "OK," indicating a successful request. Status 201 means "Created," indicating that the request has been fulfilled and resulted in a new resource being created.
