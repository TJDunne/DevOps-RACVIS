# __RACIVS matrix for DevOps Pipelines__   

<img src="https://user-images.githubusercontent.com/10748736/112030685-6c81be80-8b32-11eb-94b8-c2c01b8f4581.png">

## __Pipeline stage:__  Deploy  
### __Stage description:__  
Insert your description of the stage here  

| Pipeline Stage:<br>Deploy  | Client  | Product owner | Developer  | Tester  | UX  | System administrator |Security Team
|----------------------------- |-------- |-------- |-------- |-------- |-------- |--------  |---------
| Code compilation             |      I   |     A,S    |   C      |    V     |    I     |    I      |    R      |
| Unit test                    |     I    |     A,S    |    C     |    R     |    I     |    C      |    I      |
| Code Analysis                |     I    |     S    |    R,A     |    C     |    I     |    I      |    I      |
| Perform Test Deployment      |    I     |     S    |     A    |     R    |     I    |     C     |     I     |             
| Perform Production Deployment     I     |    S     |   A      |    C     |     I    |    R     |      I    |
| Perform Canary Deployment    |    S     |    A     |   C      |    I     |    I     |   R       |     I     |
  
  
[Home](../index.md)
