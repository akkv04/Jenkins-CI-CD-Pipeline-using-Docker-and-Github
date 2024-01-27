# Jenkins-CI-CD-Pipeline-using-Docker-and-Github
This repository contains the configuration and setup for a Jenkins CI/CD pipeline using Docker for containerization and GitHub for version control.

## Introduction
The CI/CD pipeline helps to automate building, testing, and deploying the  application whenever changes are pushed to the GitHub repository. Pipeline is created using Jenkins and  Docker is used for the deployment process

### Prerequisites
1. EC2 Instance with Jenkins, Docker and Git
2. Github account to push the code changes

#### Workflow

<img width="648" alt="image" src="https://github.com/akkv04/Jenkins-CI-CD-Pipeline-using-Docker-and-Github/assets/64690489/c12c3e77-552a-438d-a2b4-564c3a54da4c">




















###### Steps.


<img width="727" alt="image" src="https://github.com/akkv04/Jenkins-CI-CD-Pipeline-using-Docker-and-Github/assets/64690489/076b1aff-155f-4062-9a8f-27878b6f8a9f">


<img width="679" alt="image" src="https://github.com/akkv04/Jenkins-CI-CD-Pipeline-using-Docker-and-Github/assets/64690489/0a08375c-0522-4bb9-80b6-1c2c313d2198">


<img width="658" alt="image" src="https://github.com/akkv04/Jenkins-CI-CD-Pipeline-using-Docker-and-Github/assets/64690489/07b83a88-b48b-4202-9c02-2bf5f36e1a87">

<img width="424" alt="image" src="https://github.com/akkv04/Jenkins-CI-CD-Pipeline-using-Docker-and-Github/assets/64690489/d31e47be-41f5-43f2-b94b-7ee758cd520a">

Add a Execute shell step.(we will fill it later)

<img width="665" alt="image" src="https://github.com/akkv04/Jenkins-CI-CD-Pipeline-using-Docker-and-Github/assets/64690489/23ab0215-742d-4733-8a76-02462179d7b1">

Jenkins Job will be created as 

<img width="796" alt="image" src="https://github.com/akkv04/Jenkins-CI-CD-Pipeline-using-Docker-and-Github/assets/64690489/d514a252-cf75-47f8-bc80-f05dae8165e8">


Now, we need to create a webhook, which will trigger Jenkins Pipeline when any changes are pushed to the repository



