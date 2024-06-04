**Reading Notes | 04 June 2024**

# Class 027

### *Bookmarks:*

[Passing Props to a Component](https://react.dev/learn/passing-props-to-a-component)  

[Rendering Lists](https://react.dev/learn/rendering-lists)  

[State as Snapshot](https://react.dev/learn/state-as-a-snapshot)  

[useState hook](https://react.dev/reference/react/useState)

### Summarize the five steps of thinking in React

1. Break the UI into a component hierarchy.
2. Build a static version in React.
3. Determine the minimal (but complete) representation of UI state.
4. Identify where your state should live.
5. Add inverse data flow.

### State: A Component’s Memory

**What is one reason a local variable isn’t sufficient for managing a React component?**
A local variable doesn’t trigger a re-render of the component when it changes, whereas state variables do.

**What is the argument to the useState hook, and what are the two parts of its return array?**
The argument to the `useState` hook is the initial state, and its return array contains the current state and a function to update that state.

**How can Component A access state from Component B?**  
Component A can access state from Component B by lifting the state up to a common parent and passing it down as props to both components.