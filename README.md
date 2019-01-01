# Docker
## Before docker
## Monolithic Application
 Monolithic Application describes single tired application. Here all the functionalities like user-interface, code and data access are combined into a single program from a single platform.

### Monolithic Application Diagram
<img src="../images/Monolithic.png" width=640>
![Monolithic Application](../images/Monolithic.png)

#### Drawbacks of Monolithic Application
- Here we wanna do any operation like search we have to run all the application so the performance of monolithic application is low
- Developers take lots of time to understand the system because it’s big
- Scaling Problem, if you wanna scale only specific module in application it is not feasible
- Deployment challenges, It is highly risky to deploy monolithic applications deployment time is also more
- We can’t use different technologies in monolithic. For example in your application you wanna use elasticsearch, mongodb and relational db for scaling your app it is very difficult to use multiple technologies in single application
- on each update you have to redeploy all the application
- Another problem with monolithic applications is reliability. Bug in any module (e.g. memory leak) can potentially bring down the entire process

### Service Oriented Application:
A Service oriented architecture is essentially a collection of services. These services communicate with each
other. The communication can involve either simple data passing or it could involve two or more services coordinating some activity. Some means of connecting services to each other needed.
- Monolithic Application is divided into multiple projects
- Every application project can have its own application stack
- The services communicate using webservices (RESTful/SOAP)
