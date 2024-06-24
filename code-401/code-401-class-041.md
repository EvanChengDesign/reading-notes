**Reading Notes | 25 June 2024**

# Class 041

### *Bookmarks:*  
[React Native](https://facebook.github.io/react-native/)

## **Questions & Answers**  
### Reading: React Native

**Name three Core Components of React Native and describe what they do.**
1. **View**: A container that supports layout with Flexbox, style, touch handling, and accessibility controls.
2. **Text**: A component for displaying text, supporting styling, nested elements, and touch handling.
3. **Image**: A component for displaying images, supporting various image formats and providing styling options.

**What problem does React Native solve (why call it native)?**
React Native solves the problem of needing to write separate codebases for iOS and Android by allowing developers to write code once and run it on both platforms, providing a native look and feel.

**What are the building blocks of a React Native app? How does that compare to a React app?**
The building blocks of a React Native app are components like `View`, `Text`, and `Image`, which correspond to native UI elements. In a React app, the building blocks are HTML elements like `div`, `span`, and `img`. Both use components, but React Native maps to native components rather than web elements.

**What solution does Expo provide?**
Expo provides a set of tools and services to simplify the development, building, and deployment of React Native apps, including a managed workflow and a range of built-in modules.

**Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.**
managed.

**What is the difference between React Native and Expo?**
React Native is a framework for building native apps using React, while Expo is a platform built on top of React Native that provides tools and services to streamline the development process, including a managed workflow and additional APIs.

**Checkout this tool. What does snack allow you to do?**
Snack allows you to write and run React Native code directly in the browser, enabling quick prototyping and sharing of code snippets without the need for a local development environment.

**What does “eject” mean within the context of Expo?**
"Eject" means to move from the managed workflow provided by Expo to a bare workflow, giving you full control over the native code but also requiring more setup and maintenance.

**When should you not eject?**
You should not eject if you can accomplish your app’s requirements using Expo’s managed workflow, as ejecting adds complexity and maintenance overhead.

**Why might you choose to eject?**
You might choose to eject if you need to use custom native modules or dependencies that are not supported by Expo’s managed workflow, or if you need more control over the native code for advanced customization.
