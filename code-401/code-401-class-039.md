**Reading Notes | 21 June 2024**

# Class 039

### *Bookmarks:*  
[Redux Toolkit (RTK)](https://redux-toolkit.js.org/)  

[HookState](https://hookstate.js.org/)
## **Questions & Answers**  
### Readings: Redux - Additional Topics

**What concerns are addressed by Redux Toolkit?**
Redux Toolkit addresses concerns such as simplifying the setup of a Redux store, reducing boilerplate code, and providing a standardized approach to writing Redux logic.

**What does configureStore() do?**
`configureStore()` sets up a Redux store with good defaults, including combining reducers, adding middleware, enabling the Redux DevTools Extension, and more.

**How would I use createSlice()?**
You use `createSlice()` to create a slice of the Redux state, which includes generating action creators and action types based on the reducer functions defined in the slice.

**What is MobX?**
MobX is a state management library that makes state management simple and scalable by using reactive programming principles.

**How does MobX make it “impossible” to produce an inconsistent state?**
MobX makes it "impossible" to produce an inconsistent state by automatically tracking and reacting to state changes, ensuring that all derived state and computed values are always consistent and up-to-date.

**How would we build a reactive user interface?**
We build a reactive user interface by using state management libraries like MobX or Redux, which allow the UI to automatically update in response to changes in the underlying state.

**What take-away(s) did this tutorial provide?**
The tutorial on Redux Toolkit provided insights into simplifying Redux setup and usage, emphasized reducing boilerplate code, and demonstrated practical examples of creating slices, setting up the store, and handling asynchronous actions efficiently.
