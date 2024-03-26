# **Reading Notes | 26 MAR 2024**

# Class 002

### *Bookmarks:*

[React Docs - State and Lifecycle](https://reactjs.org/docs/state-and-lifecycle.html)  

[React Docs - handling events](https://reactjs.org/docs/handling-events.html)  

[React Tutorial through ‘Developer Tools’](https://reactjs.org/tutorial/tutorial.html)  

[React Bootstrap Documentation](https://react-bootstrap.github.io/)  

[Bootstrap Cheatsheet](https://getbootstrap.com/docs/5.0/examples/cheatsheet/)  

[Bootstrap Shuffle - a class “sandbox”](https://bootstrapshuffle.com/classes)  

[Netlify](https://www.netlify.com/)  
  
## **Questions & Answers**  

**Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?**

The `constructor` happens first, followed by `render`, and then `componentDidMount`.

**What is the very first thing to happen in the lifecycle of React?**

The `constructor` method is the very first thing to happen in the lifecycle of React.

**Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates**

The order is: `constructor`, `render`, `componentDidMount`, `React Updates`, `componentWillUnmount`.

**What does componentDidMount do?**

`componentDidMount` is a lifecycle method in React that is invoked immediately after a component is mounted (inserted into the DOM).

**What types of things can you pass in the props?**

You can pass any data type (string, number, array, object, function, etc.) as props in React.

**What is the big difference between props and state?**

Props are immutable and are passed from parent to child components, while state is mutable and controlled internally by the component itself.  

**When do we re-render our application?**

The application re-renders whenever there is a change in state or props.

**What are some examples of things that we could store in state?**

Examples of things to store in state include component-specific data such as form inputs, UI state (like visibility of a modal), or data fetched from an API.
