# capstone-html# Continuous deployment pipeline to deploy simple html website to AWS EKS cluster using CircleCI

This is a simple CICD pipeline using CircleCI that simplifies how to automatically deploy a container to an aws eks cluster.

### Requirements

- CircleCI
- AWS EKS (Kubernetes)
- Dockerhub
- GITLHUB

1. Create the CircleCI account
   Add the AWS credentials as environment variables. Configure `AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY` and `AWS_DEFAULT_REGION` as CircleCI project or context environment variables

2. Create a GitHub repository

### Implementation Steps

- Create a `index,html` file and make sure it is working
- Create a Docker File
- Build and tag the image
- Push the image to Docker Hub
- Create EKS cluster
- Create Deployment and Service for EKs cluster
- Deploy the image to EKS
