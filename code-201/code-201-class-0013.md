# **Reading Notes | 06 MAR 2024**

# Class 013

### *Bookmarks:*

[The Past, Present, and Future of Local Storage for Web Applications](http://diveinto.html5doctor.com/storage.html)

## **Questions & Answers**  

### Why would a developer use local storage for a web application?  

Developers might use local storage for a web application for several reasons:

* Persistent Data Storage: Local storage allows storing data persistently on the client-side browser. This means that even if the user refreshes the page or closes the browser and reopens it, the data will still be available.

* Improved Performance: Storing data locally can improve the performance of web applications by reducing the need to fetch data from a server repeatedly. This can be particularly useful for caching frequently accessed data or user preferences.

* Offline Support: Local storage enables web applications to work offline or with limited connectivity by storing essential data on the client-side. This can provide a better user experience in scenarios where internet connectivity is unreliable.

* Reduced Server Load: By storing data locally, web applications can reduce the load on the server, leading to improved scalability and cost-effectiveness, especially for applications with a large user base.  

### What information should not be stored in local storage?  

* Sensitive Personal Information: Local storage should not be used to store sensitive personal information such as passwords, credit card numbers, social security numbers, or any other sensitive data that could be exploited if accessed by unauthorized parties.

* Session Tokens: Storing session tokens or authentication tokens in local storage can expose users to security risks such as session hijacking or cross-site scripting attacks. It's better to use secure HTTP cookies or other more secure storage mechanisms for such tokens.

* Large Data: Storing large amounts of data in local storage can degrade performance and consume excessive browser memory, impacting the overall user experience. It's advisable to store only essential data in local storage and implement proper data management strategies.

* Sensitive Application State: Critical application state or sensitive business logic should not be stored in local storage as it can be tampered with or manipulated by users, potentially compromising the integrity of the application.  

### Local storage can store what type of data? How would you convert it to that type before storing?  

Local storage in web browsers stores data as strings. However, developers can store various types of data by converting them to strings before storing. When retrieving data from local storage, you can convert it back to its original type using appropriate methods (parseInt() for numbers, JSON.parse() for objects and arrays, etc.).
Here's how you can convert different types of data to strings for storing in local storage:

* Strings: No conversion is needed; you can directly store strings in local storage.

* Numbers: Convert numbers to strings using the toString() method or concatenation. For example:

      var number = 42;  
      localStorage.setItem('number', number.toString());

* Objects: Convert objects to JSON strings using JSON.stringify(). For example:  
  
      var obj = { key: 'value' };  
      localStorage.setItem('object', JSON.stringify(obj));  

* Arrays: Convert arrays to JSON strings using JSON.stringify(). For example:  
  
        var arr = [1, 2, 3];  
        localStorage.setItem('array', JSON.stringify(arr));