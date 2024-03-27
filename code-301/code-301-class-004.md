# **Reading Notes | 28 MAR 2024**

# Class 004

### *Bookmarks:*
[React Bootstrap - Forms](https://react-bootstrap.github.io/docs/forms/overview)  

[React Docs - conditional rendering](https://react.dev/learn/conditional-rendering)

## **Questions & Answers**  
  
**What is a ‘Controlled Component’?**

A controlled component is a form element whose value is controlled by React state, enabling React to be the "single source of truth" for the input's value.

**Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.**

It's better to update the state with the user's responses as soon as they enter them to provide a smoother user experience and reflect immediate changes.

**How do we target what the user is entering if we have an event handler on an input field?**

We can target what the user is entering by accessing the `event.target.value` property within the event handler function.

**Why would we use a ternary operator?**

A ternary operator is used to write concise conditional statements in JavaScript, which can improve code readability and reduce the number of lines required.

**Rewrite the following statement using a ternary statement:**

```javascript
console.log(x === y ? true : false);
