# Apexon Casestudy

TL; DR

Points to consider beforehand:

- Low bandwidth at customer location
- Knowledge of the customers or users in the latest technologies of software is low
- Customer organization may or may not have IT teams for support

### To address the issue of deploying application in low bandwidth internet speed folowing points should be taken consideration:

To minimize the size of the deployment.
To minimize the amount of data being transferred.

### To address the issue of limited knowledge of the customers

Try to make use of the customer's preferred legacy tools.


### As a DevOps Engineer, Design the DevSecOps pipeline which enables
1. Continuous integration, Delivery and Deployment
2. Continuous feedback mechanism
3. Artifacts of the product company &amp; assets of customers are secured
4. Smooth functioning of the deployment once installed or upgraded



Security should be applied to each phase of the typical DevSecOps pipeline. 

Plan
Code
Build
Test
Release
Deploy
Operate
Monitor


Planning includes selection of different technology/tools, environment.

It should also constitute a well balanced architecture (trade-off betwen quality and cost) to have a roadmap in successfully reaching the project goals.

Need to have the list of relevant tools for the pipeline.

| Class/category  | Solution  |
|---|---|
| Orchestrator  | Jenkins, GitLab, GoCD, TeamCity  |
| Source code repo  | GitHub, Bitbucket, CodeCommit, SVN  |
| Container ecosystem  | Docker, CoreOS, Rocket, Swarm, Kubernetes, ECS  |
| SAST  | Coverity  |
| Code coverage  |  Cobertura |
| Static code analysis  | Sonar, ESLint, Lint  |
| Functional test  |  Selenium |
| Performance test  | JMeter, BlazeMeter (JMeter on the cloud)  |
| Unit test  |  JUnit,Jasmine  |
|  Build | Npm, Maven  |
