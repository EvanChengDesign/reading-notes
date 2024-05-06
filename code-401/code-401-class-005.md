 **Reading Notes | 6 MAY 2024**

# Class 005

### *Bookmarks:*
[bcrypt docs](https://www.npmjs.com/package/bcrypt)  

[OWASP auth cheatsheet](https://www.owasp.org/index.php/Authentication_Cheat_Sheet)

## **Questions & Answers**  
### Explain to a Non-Technical Friend How You Would Safely Hash and Store a Password
To keep a password safe, we turn it into a secret code (hash it) using a special formula before saving it. This way, even if someone sees the stored password, they can't understand or use it.

### What is Bcrypt?
Bcrypt is a method used to hash passwords. It is designed to be slow to process, which helps protect against attempts to guess passwords quickly.

### Why Might You Use Something Like Bcrypt?
Bcrypt is used because it adds security against hacking attempts that try to guess passwords. Its slow processing time makes these attacks time-consuming and impractical.

### What is Basic Authentication?
Basic Authentication is a simple security method for websites where a user provides a username and password to access a page. The server checks these credentials before allowing access.

### What Properties are Necessary in the Header of a Basic Auth Request?
The header of a Basic Auth request must include a `Authorization` field with the value starting with `Basic` followed by a space and the base64-encoded string of `username:password`.

### How are Username:Password in Basic Auth Encoded?
In Basic Authentication, the username and password are combined with a colon (`username:password`), then this combination is encoded in Base64.

### Define the Authentication Process to a Non-Technical Recruiter
Authentication is like checking an ID at a club entrance. When you enter a username and password, the server checks them against its records. If they match, you get access; if not, access is denied.

### How Should Your Error Messaging Respond (Both HTTP and HTML)? Why?
Error messages should be clear but not give away details that could help an attacker (like whether a username exists). For HTTP, use status codes like 401 for unauthorized access. In HTML, generic messages like "Login failed" are safe and user-friendly.

### Looking ahead at this module’s course schedule, What do you look forward to learning?
I look forward to learning about AWS and what that entails.

### What are your learning goals after reading and reviewing the class README?

To become proficient in understanding the technical concepts of JavaScript and have an ability to explain the logic, time and space considerations for these functions.

