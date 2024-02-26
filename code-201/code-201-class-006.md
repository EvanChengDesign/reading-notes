# **Reading Notes | 26 FEB 2024**

# Class 006  

### *Bookmarks:*

[What’s the Difference Between Primitive Values and Object References in JavaScript?](https://betterprogramming.pub/intermediate-javascript-whats-the-difference-between-primitive-values-and-object-references-e863d70677b)

[How to Solve Programming Problems](https://simpleprogrammer.com/solving-problems-breaking-it-down/)
  
## **Notes Outline:**

Readings: Problem Domain, Objects, and the DOM

## **Questions & Answers**  

1. ### How would you describe an object to a non-technical friend you grew up with?

    Describing an object to a non-technical friend might involve likening it to something familiar, like a toolbox. I'd explain that an object is like a toolbox where you can keep different tools (properties) organized. Each tool has a specific purpose, just like each property in an object serves a specific role.

2. ### What are some advantages to creating object literals?  

    1. They provide a convenient way to group related data and functionality together.  

    2. Object literals allow for easy creation of complex data structures.

3. ### How do objects differ from arrays?  

    Objects and arrays are both data structures in JavaScript, but they serve different purposes:

     * Objects are collections of key-value pairs, where each value is accessed by its associated key (also called a property). Objects are typically used to represent entities with properties and behaviors.  

    * Arrays are ordered collections of values, accessed by numerical indices. They are used to store lists of data, such as a collection of items or a series of values.

4. ### Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation  

    You would need to use bracket notation to access an object's property instead of dot notation when:

    The property name is dynamic or stored in a variable. For example:

        let propName = "age";  
        let person = {name: "John", age: 30};  
        console.log(person[propName]);

5. ### Evaluate the code below. What does the term "this" refer to and what is the advantage to using "this"?  

        const dog = {
            name: 'Spot',
            age: 2,
            color: 'white with black spots'         humanAge: function (){
            console.log(`${this.name} is ${this.age*7} in human years`);
         }
        }
  
    In the provided code, this refers to the current object, which is dog.

    The advantage of using this in this context is that it allows the method humanAge to access the properties of the dog object dynamically. By using this, the method can refer to the properties of the object it belongs to without explicitly mentioning the object's name (dog). This makes the code more flexible and reusable because if the name of the object were to change, the method would still work correctly without needing to be modified.  

1. ### What is the DOM?  

    The DOM, or Document Object Model, is a programming interface for web documents. It represents the structure of HTML and XML documents as a tree-like structure where each node represents a part of the document, such as elements, attributes, and text.

2. ### Briefly describe the relationship between the DOM and JavaScript  

    1. JavaScript Manipulates the DOM.
    2. DOM Provides a Programming Interface.  
    3. Overall, JavaScript and the DOM work together to create dynamic, interactive, and responsive web applications. JavaScript provides the scripting capabilities to manipulate the DOM, while the DOM provides the structured representation of web documents that JavaScript interacts with.
