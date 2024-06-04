**Reading Notes | 03 June 2024**

# Class 026

### *Bookmarks:*
[Your First Component](https://react.dev/learn/your-first-component)  

[Importing and Exporting Components](https://react.dev/learn/importing-and-exporting-components)  

[Writing Markup with JSX](https://react.dev/learn/writing-markup-with-jsx)

## **Questions & Answers**  
### What are the building blocks of a React app?
The building blocks of a React app are components, which can be functional or class-based, and manage the UI and state of the application.

### What is the difference between an HTML element and a React component?
An HTML element is a basic building block of a web page, while a React component is a self-contained module that can manage its own state and lifecycle and can include other React components or HTML elements.

### What is JSX and why do we use it?
JSX is a syntax extension for JavaScript that allows you to write HTML-like code within JavaScript, making it easier to create and visualize React components.

### Describe the process of embedding JavaScript expressions in JSX.
JavaScript expressions can be embedded in JSX by wrapping them in curly braces `{}`, allowing dynamic data to be displayed in the rendered output.

### Does React or JSX have any special features for iteration or conditional logic?
JSX does not have special features for iteration or conditional logic, but JavaScript functions like `map()`, `filter()`, and conditional operators can be used within JSX.

### How does React know to respond to a user’s inputs?
React responds to user inputs through event handlers, which can be attached to elements and components, and update the component state when triggered.

### What word indicates that a React component manages data with a Hook?
The word "use" indicates that a React component manages data with a Hook, such as `useState` or `useEffect`.

### How can two React components share data?
Two React components can share data by lifting the state up to a common ancestor component or by using context to provide data throughout the component tree.

### What are the three steps of refreshing a React UI?
The three steps of refreshing a React UI are: updating the component state, re-rendering the component, and updating the DOM.

### How do you trigger updates to a component after the initial render?
Updates to a component after the initial render are triggered by changing the component's state or props.

### Does React recreate DOM nodes on every rerender?
React does not recreate DOM nodes on every rerender; it uses a virtual DOM to optimize and update only the parts of the DOM that have changed.

### After React has updated the DOM, what still needs to happen before the user sees the change?
After React has updated the DOM, the browser needs to repaint and reflow the layout before the user sees the change.

### Note the naming conventions in the Airbnb React/JSX Style Guide. What pattern(s) do you see?
The Airbnb React/JSX Style Guide recommends using PascalCase for component names and camelCase for props and attributes, emphasizing clarity and consistency.
