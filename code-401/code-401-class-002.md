 **Reading Notes | 30 APR 2024**

# Class 002

### *Bookmarks:*
[nodeJS docs](https://nodejs.org/en/docs/)  
[npm docs](https://docs.npmjs.com/)  
[express docs](https://expressjs.com/en/4x/api.html)  
[http status codes](https://www.restapitutorial.com/httpstatuscodes.html)  
[supertest](https://github.com/visionmedia/supertest)

## **Questions & Answers**  

### Explain middleware, answer as though I were a non-technical recruiter.
Middleware is like a helper that manages the flow of data between systems or within a system. It acts as a bridge, making sure that different parts of an application can communicate effectively and perform tasks like checking who is logged in or processing data forms.

### Express the most popular __ __ ____.
The most popular *JavaScript framework* is Express.js. It is widely used to build web applications, especially APIs.

### Express is “unopinionated.” What does that mean?
Being "unopinionated" means that Express does not enforce a strict way of building an application. It gives developers the flexibility to use whatever structure or libraries they prefer, making it easier to tailor the application to specific needs.

### What is a module and why is modularity useful to us as developers?
A module is a separate piece of software that handles a specific task and can be used independently. Modularity is useful because it allows developers to break down complex software into manageable parts, making it easier to develop, understand, maintain, and reuse code.

### What version of npm are you running on your machine?
I am currently running 10.5.0

### What command would you type to install a library/package called ‘jshint’ into your node project?

npm install jshint --save-dev

### Explain why tests are important. Please explain as though I were your non-technical elder.
Tests are important because they are like health check-ups for a software application. They ensure that the software works correctly and safely, just as doctors check that our body functions properly, helping to prevent future problems.

### What are three expected benefits of testing?
1. **Identifying defects early:** Testing helps catch issues before the software is released, reducing the cost and effort of fixing them later.
2. **Improving quality:** Consistent testing improves the overall reliability and performance of the software.
3. **Facilitating updates:** With thorough testing, developers can make changes or add features with confidence, knowing it won’t unexpectedly break the software.

### Name at least 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.
**Individual Pitfalls:**
- Writing tests that are too complex, making them hard to understand and maintain.
- Not updating tests after changes in the application, leading to false results.

**Team Pitfalls:**
- Lack of communication, resulting in duplicated efforts or gaps in test coverage.
- Inconsistent testing standards across team members, leading to uneven software quality.

### What are three benefits of Continuous Integration?
1. **Immediate feedback on errors:** Developers find out quickly if their changes conflict with existing code, allowing for quicker fixes.
2. **Reduced integration problems:** Regularly merging code changes reduces the complexity of integration challenges.
3. **Faster delivery times:** Continuous integration helps speed up the release process by automating parts of the development.

### What is the difference between Continuous Delivery and Continuous Deployment?
Continuous Delivery is a practice where code changes are automatically prepared for a release to production, whereas Continuous Deployment goes a step further by automatically releasing every change that passes the test phase into production, without human intervention.

### Explain how GitHub fits into this process assuming the listener comes from a non-technical background
GitHub acts like a library for computer code, where developers store their projects. It also helps them collaborate by tracking changes and combining updates from different team members efficiently. In terms of Continuous Integration and Deployment, GitHub can automatically run tests and prepare software to be released, making the whole process more streamlined and error-free.


### What are your learning goals after reading and reviewing the class README? 
I hope to have a better conceptual grasp on server testing and how to troubleshoot without actually launching a server.
