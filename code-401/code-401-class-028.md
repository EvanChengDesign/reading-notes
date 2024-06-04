**Reading Notes | 05 June 2024**

# Class 028

### *Bookmarks:*
[Responding to Events](https://react.dev/learn/responding-to-events)  
[Conditional Rendering](https://react.dev/learn/conditional-rendering)  
[Updating Arrays in State](https://react.dev/learn/updating-arrays-in-state)  
[Updating Objects in State](https://react.dev/learn/updating-objects-in-state)

## **Questions & Answers**  
**What is the main intended use case for the useEffect hook?**  
The useEffect hook is primarily intended for handling side effects in functional components, such as fetching data, subscribing to events, or manipulating the DOM.

**How does the effect’s logic interact with the component?**  
The effect’s logic runs after the component renders, allowing it to perform actions based on the latest render output and optionally clean up before the component unmounts or before the effect runs again.

**What is the importance of the return value from the effect’s logic function?**  
The return value from the effect’s logic function is used for cleanup; it’s a function that React calls to clean up any side effects from the previous render before running the effect again or before unmounting the component.

