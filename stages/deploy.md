# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Deploy  
### __Stage description:__  
Insert your description of the stage here  

In this phase, the code is deployed to the production servers. Also, it is essential to ensure that the code is correctly used on all the servers.
The new code is deployed continuously, and configuration management tools play an essential role in executing tasks frequently and quickly. Here are some popular tools which are used in this phase, such as Chef, Puppet, Ansible, and SaltStack.

Containerization tools are also playing an essential role in the deployment phase. Vagrant and Docker are popular tools that are used for this purpose. These tools help to produce consistency across development, staging, testing, and production environment. They also help in scaling up and scaling down instances softly.

Containerization tools help to maintain consistency across the environments where the application is tested, developed, and deployed. There is no chance of errors or failure in the production environment as they package and replicate the same dependencies and packages used in the testing, development, and staging environment. It makes the application easy to run on different computers.

| Pipeline Stage:<br>Deploy  | Client  | Product owner | Developer  | Tester  | System administrator |Security Team
|----------------------------- |-------- |-------- |-------- |--------  |--------  |---------
| Code compilation             |      I   |     A,S    |   C      |    V     |    I      |    R      |
| Unit test                    |     I    |     A,S    |    C     |    R      |    C      |    I      |
| Code Analysis                |     I    |     S    |    R,A     |    C      |    I      |    I      |
| Perform Test Deployment      |    I     |     S    |     A    |     R     |     C     |     I     |             
| Perform Production Deployment |    I     |    S     |   A      |    C      |    R     |      I    |
| Perform Canary Deployment    |    S     |    A     |   C      |    I     |   R       |     I     |
  
  
[Home](../index.md)
