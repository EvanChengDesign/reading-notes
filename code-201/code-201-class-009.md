# **Reading Notes | 29 FEB 2024**

# Class 009

### *Bookmarks:*

[HTML 5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)  
[Event Reference](https://developer.mozilla.org/en-US/docs/Web/Events)

## **Questions & Answers**  

### Why are forms so important in web development?  
  
  Forms are crucial in web development as they facilitate user interaction and data collection, enabling users to submit information to websites, make purchases, sign up for services, and more.

### When designing a form, what are some key things to keep in mind when it comes to user experience?  

When designing a form for optimal user experience, consider factors like clarity, simplicity, intuitive layout, error handling, responsive design, and accessibility to ensure users can easily understand and complete the form without frustration.

### List 5 form elements and explain their importance.  

Five important form elements include:

    1. Text Input: Allows users to enter text-based information like names, addresses, or messages.  

    2. Dropdown Menus: Provide users with a predefined list of options to select from, ensuring uniform data input.

    3.Radio Buttons: Enable users to choose a single option from a set of mutually exclusive choices.

    4. Checkboxes: Allow users to select multiple options from a list, suitable for tasks like selecting preferences or agreeing to terms.

    5. Submit Button: Initiates the form submission process, sending the entered data to the server for processing.  

### How would you describe events to a non-technical friend?  
  
  Events are like triggers in programming that are activated by user actions (like clicks or keyboard inputs) or by the system (like page loading). They allow code to respond dynamically to user interactions, enabling interactive web experiences.

### When using the addEventListener() method, what 2 arguments will you need to provide?  
  
When using the addEventListener() method, you need to provide two arguments: the type of event you want to listen for (e.g., "click," "submit") and the function to be executed when the event occurs.

### Describe the event object. Why is the target within the event object useful?

The event object contains information about the event that occurred, such as the type of event, the element that triggered the event (target), and additional properties related to the event. The target within the event object is useful because it allows developers to access the specific element that triggered the event, enabling them to perform actions based on that element's attributes or properties.

### What is the difference between event bubbling and event capturing?

Event bubbling refers to the propagation of an event from the target element to its parent elements in the DOM hierarchy, while event capturing involves the opposite: the event is captured from the outermost parent down to the target element. Both mechanisms allow for handling events at different levels of the DOM tree and can be useful in managing event propagation and delegation.
