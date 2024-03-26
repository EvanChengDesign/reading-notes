# **Reading Notes | 27 MAR 2024**

# Class 003

### *Bookmarks:*
[React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)  

[React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)

## **Questions & Answers**  
  
**What does .map() return?**  

.map() returns a new array populated with the results of calling a provided function on every element in the calling array.

**If I want to loop through an array and display each value in JSX, how do I do that in React?**  

You can use the .map() function to loop through the array and return JSX elements for each value.

**Each list item needs a unique ____.**  

Each list item needs a unique key.

**What is the purpose of a key?**  

The purpose of a key in React is to uniquely identify elements in a list, helping React identify which items have changed, are added, or are removed.

**What is the spread operator?**  

The spread operator (...) in JavaScript is used to expand elements of an iterable like an array or an object.

**List 4 things that the spread operator can do.**  

The spread operator can clone arrays, merge arrays, clone objects, and merge objects.

**Give an example of using the spread operator to combine two arrays.**  

const combinedArray = [...array1, ...array2];

**Give an example of using the spread operator to add a new item to an array.**  

const newArray = [...oldArray, newItem];

**Give an example of using the spread operator to combine two objects into one.**  

const combinedObject = { ...obj1, ...obj2 };

**In the video, what is the first step that the developer does to pass functions between components?**  

The developer creates a function in the parent component.

**In your own words, what does the handleClick function do?**  

The handleClick function is triggered when a specific event (like a button click) occurs, and it typically performs some action or sets some state in response to that event.

**How can you pass a method from a parent component into a child component?**  

You can pass a method from a parent component to a child component as a prop.

**How does the child component invoke a method that was passed to it from a parent component?**  

The child component can invoke the passed method by calling it like a regular function within its own scope, usually triggered by certain events or lifecycle hooks.
  