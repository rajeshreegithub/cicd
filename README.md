# Project Overview
This project demonstrates a Continuous Integration and Continuous Deployment (CI/CD) pipeline for a Node.js application. The pipeline includes manual deployment to AWS EC2, automation using Docker, and also a pipeline built using GitHub Actions with a webhook integration.

## Manual Deployment to AWS EC2
1. Set up an AWS EC2 instance.
2. Install Jenkins on the EC2 instance.
3. Create a new Jenkins job for the Node.js application.
4. Configure the job to check out the code from a source code repository.
5. Add build steps to compile and package the code.
6. Add a post-build action to deploy the code to the EC2 instance.

## Automation using Docker
1. Create a Docker image for the Node.js application.
2. Modify the Jenkins job to use the Docker image instead of building the code directly.
3. Update the post-build action to deploy the Docker container to the EC2 instance.

## CI/CD pipeline using GitHub Actions and Webhook Integration
1. Create a new GitHub Actions workflow for the Node.js application.
2. Add steps to build and package the code.
3. Enable the GitHub Actions workflow for the repository.
4. Add a webhook to trigger the workflow when changes are pushed to the repository.

## Conclusion
This CI/CD pipeline provides a robust and automated solution for deploying a Node.js application to AWS EC2. By using Docker, the pipeline can be easily adapted to different environments and scaled as needed. The integration with GitHub Actions and the use of a webhook make it easy to keep the pipeline up-to-date with the latest changes to the code.
