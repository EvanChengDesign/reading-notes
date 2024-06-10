**Reading Notes | 10 June 2024**

# Class 031

### *Bookmarks:*  
[Sharing State Between Components](https://react.dev/learn/sharing-state-between-components)  

[Preserving and Resetting State](https://react.dev/learn/preserving-and-resetting-state)  

## **Questions & Answers**  

**Summarize the five principles for structuring state:**
1. **Single Source of Truth:** Ensure state is kept in one place.
2. **State is Read-Only:** State can only be modified by actions.
3. **Minimal State:** Keep only essential state and compute derived data.
4. **Lift State Up:** Move state to the nearest common ancestor if shared.
5. **Keep State Close:** Maintain state within relevant components when possible.

**What problem do Contexts aim to solve?**
Contexts aim to solve the problem of prop drilling by providing a way to pass data through the component tree without having to pass props down manually at every level.

**What is one technique to try before useContext?**
Before using `useContext`, try lifting state up to the nearest common ancestor to share state between components.

**What hook complements useContext for complex applications?**
The `useReducer` hook complements `useContext` for managing complex state logic in applications.
