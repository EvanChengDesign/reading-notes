**Reading Notes | 21 MAY 2024**

# Class 016

### *Bookmarks:*
[Virtual Machines](https://www.youtube.com/watch?v=yIVXjl4SwVo)  
[VMS and the Cloud](https://www.youtube.com/watch?v=l0DfHUWMjsU)  

## **Questions & Answers**
### What is an EC2 Instance?
An EC2 instance is a virtual server in Amazon's Elastic Compute Cloud (EC2) for running applications on the AWS infrastructure.

### Name 2 use cases for EC2.
1. Hosting scalable web applications.
2. Running batch processing jobs.

### Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.
ECS provides deeper integration with other AWS services and greater control over containerized applications' configuration and deployment.

### Where can we find EC2 on the AWS Console?
You can find EC2 under the "Compute" section on the AWS Management Console.

### Explain the general difference between T2 Micro and XL.
T2 Micro is a low-cost instance type with minimal resources suitable for low-traffic applications, while T2 XL provides more CPU and memory for higher demand workloads.

### Explain a “Compute Cycle” to a non-technical friend.
A compute cycle is like a single step in a task a computer performs; just as baking a cake involves many steps, running a program involves many compute cycles.

### What is Elastic Beanstalk?
Elastic Beanstalk is an AWS service for deploying and managing applications without worrying about the underlying infrastructure.

### Describe the relationship between EC2 and Elastic Beanstalk.
Elastic Beanstalk uses EC2 instances to run the applications you deploy, handling the provisioning and management of these instances automatically.

### Name some benefits of using Elastic Beanstalk.
1. Simplified deployment and management of applications.
2. Automatic scaling to handle varying levels of traffic.
3. Integration with other AWS services for a comprehensive cloud solution.
