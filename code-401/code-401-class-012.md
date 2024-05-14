 **Reading Notes | 14 MAY 2024**

# Class 012

### *Bookmarks:*

[Socket.io Documentation](https://socket.io/docs/)
[Socket.io Server API](https://socket.io/docs/server-api)
[Socket.io Client API](https://socket.io/docs/client-api)
[Socket Testing Tool](https://amritb.github.io/socketio-client-tool/)

## **Questions & Answers**

### What is a Web Socket?
A WebSocket is a communication protocol that provides full-duplex communication channels over a single TCP connection.

### Describe the Web Socket request/response handshake and what happens once the connection is established.
The WebSocket handshake starts with an HTTP request from the client to the server, which then upgrades the connection to WebSocket. Once established, the connection allows for bidirectional, real-time data transfer.

### Web Sockets provide a standardized way for the server to send content to a client without first receiving a ____ from that client.
request

### What does the event handler `io.on()` do?
The `io.on()` event handler listens for and responds to specific events, allowing the server to execute code when those events are triggered.

### Describe some possible proof of life or proof that the code works as expected.
Proof of life for the code could include successfully establishing a WebSocket connection, receiving expected messages, and performing correct real-time data updates.

### What does `socket.emit()` do?
The `socket.emit()` function sends a message to the server or a specific client, triggering an event handler on the receiving end.

### What is the difference between WebSocket and Socket.IO? (think Git and GitHub, or OAuth and Auth0).
WebSocket is a protocol for bidirectional communication, whereas Socket.IO is a library that abstracts WebSocket and provides additional features like fallback options, automatic reconnection, and event-based communication.

### When would you use Socket.IO?
You would use Socket.IO when you need a robust solution for real-time communication that includes features like automatic reconnection, broadcasting, and event handling.

### When would you use WebSockets?
You would use WebSockets for real-time communication when you need a lightweight, low-latency solution and can manage connections and fallbacks manually.

### What are a couple of key takeaways from this video?
1. WebSockets enable real-time, bidirectional communication between clients and servers.
2. Socket.IO enhances WebSockets with additional features and reliability, making it easier to implement in various applications.

### Translate the gist of this video to a non-technical friend
WebSockets let websites talk to servers instantly without waiting, making things like chat and live updates super fast. Socket.IO makes it even easier by adding extra tools to handle different issues and improve reliability.
