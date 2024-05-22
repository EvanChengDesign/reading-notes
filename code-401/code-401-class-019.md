**Reading Notes | 23 MAY 2024**

# Class 019

### *Bookmarks:*
[SNS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SNS.html)  

[SQS Javascript SDK](https://docs.aws.amazon.com/AWSJavaScriptSDK/latest/AWS/SQS.html)  

## **Questions & Answers**  
### What is the difference between SQS and SNS?
SQS (Simple Queue Service) is a message queuing service that decouples components of a distributed system by transmitting messages between them, while SNS (Simple Notification Service) is a pub/sub messaging service that enables message delivery to multiple subscribers.

### What are some use cases for both SNS and SQS?
Use cases for SQS include asynchronous communication between microservices, buffering requests, and handling background tasks. SNS is used for broadcasting notifications to multiple subscribers, such as sending alerts, notifications, and updates.

### Describe how to use SQS and SNS in a “fanout” pattern.
In a "fanout" pattern, SNS publishes messages to a topic, and multiple SQS queues subscribe to this topic. Each queue receives a copy of the message, enabling parallel processing or distribution of tasks among different components.

### Explain how “push notifications” work, using SNS.
Push notifications involve sending messages or updates directly to mobile devices or endpoints. Using SNS, the application sends a notification to a subscribed endpoint (e.g., mobile device) via a push notification service (e.g., Apple Push Notification Service for iOS or Firebase Cloud Messaging for Android).

### How might a large scale, distributed application make use of a Queue system like SQS?
In a large-scale, distributed application, SQS can be used to decouple components, manage traffic spikes, and ensure fault tolerance by providing a buffer for incoming requests. It helps maintain system reliability and scalability by processing messages asynchronously and distributing workloads across multiple instances or services.
