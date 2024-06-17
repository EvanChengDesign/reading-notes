**Reading Notes | 13 June 2024**

# Class 034

## **Questions & Answers**
### Explain the difference between a query string parameter and a path parameter.

**Query string parameters** are part of the URL that follows a `?` and provide key-value pairs for filtering or specifying additional information. **Path parameters** are part of the URL structure itself, typically used to specify a particular resource within the API.

### What would our API URL with a path id parameter be given the following information:

**Domain:** `http://our-site.com`  

**Version:** `v3`  

**Model name:** `stuff`  

**ID:** `things`

**API URL:** `http://our-site.com/v3/stuff/things`

### We have created a dynamic API with an “interface”. Describe how that interface works to a non-technical friend.

An **API interface** allows different software systems to communicate with each other. It's like a menu in a restaurant that lists all the options you can order; the API interface lists all the actions you can request from the software, like getting information or sending data.

### Review Auth Server Build

**Describe how you would use middleware to implement basic and bearer auth.**

In **middleware for basic auth**, the server decodes the username and password sent in the request headers and checks them against stored credentials. For **bearer auth**, the middleware verifies a token sent in the headers and ensures it's valid and not expired.

**Describe the handshake necessary to implement OAuth.**

In **OAuth**, the handshake involves the client requesting authorization from the user, the user granting permission, the client receiving an authorization code, and then the client exchanging that code for an access token from the authorization server, which allows access to the user's resources.

**Describe how Role Based Access Control works to a non-technical friend.**

**Role Based Access Control (RBAC)** is like assigning different access levels to members of a club. Depending on their role, members can access certain areas or perform specific actions. For example, a regular member might only view content, while an admin can add or delete content.

