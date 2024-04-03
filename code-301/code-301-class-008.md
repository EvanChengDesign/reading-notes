# **Reading Notes | 03 APR 2024**

# Class 008

### *Bookmarks:*  
[RegExr - Pay particular attention to the cheatsheet](https://regexr.com/)  

[Regex Tutorial](https://medium.com/factory-mind/regex-tutorial-a-simple-cheatsheet-by-examples-649dc1c3f285)  

[Regex 101](https://regex101.com/)

## **Questions & Answers**  

### What does REST stand for?

REST stands for Representational State Transfer.

### REST APIs are designed around a ____

REST APIs are designed around a **resource**.

### What is an identifier of a resource? Give an example

An identifier of a resource is a unique URI that points to that resource. For example, `https://api.example.com/users/123`.

### What are the most common HTTP verbs?

The most common HTTP verbs are **GET**, **POST**, **PUT**, **DELETE**, and **PATCH**.

### What should the URIs be based on?

The URIs should be based on **nouns** (the resources) and not verbs (the operations on the resources).

### Give an example of a good URI

An example of a good URI is `https://api.example.com/users`.

### What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?

Having a ‘chatty’ web API means that it requires multiple requests to complete a single operation. This is generally considered a bad thing because it can lead to increased load times and inefficiency.

### What status code does a successful GET request return?

A successful GET request returns a **200 OK** status code.

### What status code does an unsuccessful GET request return?

An unsuccessful GET request often returns a **404 Not Found** status code, among other possible errors.

### What status code does a successful POST request return?

A successful POST request returns a **201 Created** status code.

### What status code does a successful DELETE request return?

A successful DELETE request returns a **204 No Content** status code.
