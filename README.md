# AWS CloudFormation Enhanced...
> This is an enhanced version of the original project that I submitted for Udacity Cloud DevOps Nanodegree that teaches the differences between using rolling deployments and blue/green deployments. (@TODO Create a blog or a separate doc file to detail this information)

## Project Tasks
---
- AWS Environment / Console / CLI
- Use Jenkins to implement CI/CD (Continuous Integration, Continuous Deployment)
- Build the pipelines with Jenkins
- Use AWS CloudFormation or Ansible to create and deploy clusters
    - Create a local Kubernetes cluster for testing
    - The Kubernetes cluster needed to be created before deploying the next step via Jenkins pipeline (i.e., deploying docker images)
- Use an existing docker image to pull or create custom docker image to build and push to the appropriate repository through the Jenkins pipelines.
- Create screenshots of the appropriate steps and errors

## Propose and Scope the Project
---
- Pipeline Setup
    - Rolling Deployment v. Blue/Green Deployment?
    - Continuous Integration Tool(s) - Jenkins?
    - Docker application (generic or custom?)
- If using Jenkins?
    - Implement Rolling Deployment or Blue/Green Deployment
    - Create a Jenkins master box in AWS environment
- AWS Kubernetes as a Service or build own Kubernetes cluster
    - Ansible or AWS CloudFormation (infrastructure as a code) to build Kubernetes cluster
        - Create EC2 instances, set the correct networking settings, and deploy software to these instances (i.e., deploy the built Docker image)
    - Kubernetes cluster will need to be initialized first by hand or with Ansible or AWS CloudFormation
- Building the Pipeline
    - Construct the pipeline in the Github repository
    - Set up the appropriates steps that the pipeline will process
    - Configure the deployment pipeline
    - Make sure Dockerfile is created and included
    - Include a Linting step (show failed and success screenshots)

## Key Things to Look For
---
