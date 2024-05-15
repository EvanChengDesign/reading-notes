 **Reading Notes | 15 MAY 2024**

# Class 013

### *Bookmarks:*
[Socket.io Emit Cheatsheet](https://socket.io/docs/v4/emit-cheatsheet/)

## **Questions & Answers**

**Explain to a non-technical recruiter what the Chat Example (above) does.**
The Chat Example demonstrates a delivery tracking system using event-driven programming with Socket.IO, enabling real-time communication between clients and the server for status updates.

**What proof of life are we getting on the backend from the above app?**
We are receiving real-time event acknowledgements and status updates from clients, ensuring the backend knows the system is active and responsive.

**Socket.IO gives us the io.emit() method to send an event to everyone. What flag would you use if you want to send a message to everyone except for a certain emitting socket?**
You would use the `broadcast` flag to send a message to everyone except the emitting socket.

**What is a room and how might a room be useful?**
A room is a subset of connections within a namespace that can communicate with each other; it's useful for creating isolated channels for specific groups of users, such as private chat rooms or team-specific updates.

**How do you join a room?**
You join a room by calling the `socket.join(roomName)` method.

**How do you leave a room?**
You leave a room by calling the `socket.leave(roomName)` method.

**What is a Namespace and what does it allow you to do?**
A Namespace is a way to separate the logic and events of different parts of your application, allowing you to create distinct channels for various functionalities or modules.

**Each namespace potentially has its own what? (hint: 3 things)**
Each namespace potentially has its own rooms, event handlers, and middleware.

**Discuss a possible use case for separate namespaces**
Separate namespaces can be used to manage different types of users or functionalities within an application, such as having one namespace for admin communications and another for user interactions, ensuring modular and organized event handling.
