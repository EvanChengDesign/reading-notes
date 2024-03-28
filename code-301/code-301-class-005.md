# **Reading Notes | 29 MAR 2024**

# Class 005

### *Bookmarks:*
[React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)  

[High Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)
## **Questions & Answers**  

### 1. What is the single responsibility principle and how does it apply to components?
The Single Responsibility Principle (SRP) states that a class or component should have one reason to change, meaning it should have only one job. In the context of components, this principle suggests that each component should be responsible for handling one specific piece of your application's functionality.

### 2. What does it mean to build a ‘static’ version of your application?
Building a 'static' version of your application means creating a version that has no interactivity or dynamic data. It involves laying out components and passing data through props but without implementing state or event handlers. This step focuses on the UI structure, not behavior.

### 3. Once you have a static application, what do you need to add?
Once you have a static application, you need to add interactivity by introducing state and event handlers. This step involves identifying where your app requires dynamic data or user interaction capabilities and implementing them accordingly.

### 4. What are the three questions you can ask to determine if something is state?
1. Is it passed in from a parent via props? If so, it probably isn’t state.
2. Does it remain unchanged over time? If yes, it likely isn’t state.
3. Can you compute it based on any other state or props in your component? If yes, it’s not state.

### 5. How can you identify where state needs to live?
To identify where state needs to live, follow these steps:
- Determine which components use or affect the state.
- Find a common parent component among these components.
- The state should be owned by the common parent component or higher up in the hierarchy.

### 6. What is a “higher-order function”?
A higher-order function is a function that either takes one or more functions as arguments or returns a function as its result. This concept is a cornerstone of functional programming, enabling powerful techniques like composition and abstraction.

### 7. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
In the context of a `greaterThan` function, line 2 typically checks if the given number is greater than a specified threshold. It returns `true` or `false` based on that comparison, effectively abstracting a comparison operation into a reusable function.

### 8. Explain how either map or reduce operates, with regards to higher-order functions.
`map` is a higher-order function that transforms each element in a collection by applying a given function to all elements in the original array, returning a new array with the transformed elements. `reduce`, on the other hand, iterates over a list of elements and applies a reducer function to accumulate a single value, which it returns; this is useful for summing numbers, aggregating data, or combining an array into a single value in a customizable way.


