**Reading Notes | 06 June 2024**

# Class 029

### *Bookmarks:*  
[useReducer hook](https://react.dev/reference/react/useReducer)  

[Keeping Components Pure](https://react.dev/learn/keeping-components-pure)  

[Queueing a Series of State Updates](https://react.dev/learn/queueing-a-series-of-state-updates)  

## **Questions & Answers**  
**What is the motivation for adding a reducer?**

Reducers centralize state management, making complex state logic easier to handle, debug, and test by ensuring state transitions are predictable and consistent.

**What are actions in the context of a reducer? How are they different than setting state directly?**

Actions are plain objects that describe an event or change in the application, allowing reducers to determine how the state should be updated, rather than directly setting state, which keeps state logic contained and more manageable.

**What common list operation is `useReducer` named for, and why?**

`useReducer` is named after the `reduce` array method, as it similarly takes a collection of inputs (actions) and reduces them into a single output (state).

**When should you switch from `useState` to `useReducer`?**

Switch to `useReducer` when state logic becomes complex, involves multiple sub-values, or when the next state depends on the previous one, benefiting from a more structured and predictable state management approach.
