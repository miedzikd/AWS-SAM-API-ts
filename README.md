# AWS-SAM-API-ts
This repository contains an example of an API implementation written in typescript using AWS SAM

### Workflow model
1. We will use reusable templates (each for one dev, one for qa and one for prod)
  ![image](https://user-images.githubusercontent.com/21012696/193752496-18837b2a-bf16-46d3-87b4-11eac5adbcf4.png)
1. When you want to know how events structure looks like you can generate this with:
    ```
    sam local generate-event s3 put
    ```
    ![image](https://user-images.githubusercontent.com/21012696/193756994-a6c90260-22e1-4445-bb36-32bade724481.png)


Resources:
- https://www.youtube.com/watch?v=QBBewrKR1qg - Mastering the AWS Serverless Application Model (AWS SAM) - AWS Online Tech Talks
