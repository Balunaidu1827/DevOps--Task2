# Jenkins CI/CD Pipeline Example

## Objective
Set up a basic Jenkins pipeline to automate the process of building and deploying an application using Docker.

## Tools Used
- Jenkins
- Docker

## Deliverable
A Jenkins pipeline file (`Jenkinsfile`) that builds and deploys a sample app.

## Setup Instructions
1. Install Jenkins locally or use a Jenkins cloud instance.
2. Install Docker.
3. Clone this repo.
4. Configure Jenkins with GitHub webhook (for auto-trigger on commit).
5. Push changes to test the pipeline.

## Jenkinsfile Pipeline Stages
- **Checkout**
- **Build Docker Image**
- **(Optional) Test**
- **Deploy**

## Sample Output
Pipeline runs on each commit. You can view logs on Jenkins Dashboard.
