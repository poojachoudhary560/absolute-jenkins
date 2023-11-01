# Introduction

## About
- Accelerate Software Development Process with Jenkins
- it is a popular automation server
- it is used to automate CI/CD pipeline

## Steps
1. Checkout code from Version Control:
It can be configuered to automatically checkout code from version control system as GitHub

2. Compile Code
Jenkins can use variety of build tools as Maven or Gradle to compile the code

3. Run Unit Tests
Jenkins can run unit tests to ensure that code is running properly

4. Build a Docker Image
Jenkins can build a docker image from the compiled code

5. Push docker image to registry
Jenkins can push docker image to docker registry as Docker Hub

6. Deploy to Kubernetes
Jenkins can notify Kubernetes of new Docker image and deploy it to Kubernetes cluster.

## Benefits

- Automated: It can automate entire CI/CD pipeline, saving a lot of time and effort
- Scalable: It can scale to handle large and complex projects
- Flexible: It can be configured to meet specific needs of a project

## Other such tools
CircleCI