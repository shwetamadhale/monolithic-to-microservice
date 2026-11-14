# Building Microservices and CI/CD Pipeline with AWS

## Overview
This project involves designing and implementing a microservices architecture using AWS services while setting up a CI/CD pipeline for continuous deployment. The objective is to transform a monolithic application into microservices, enhancing scalability, manageability, and deployment efficiency.

## Table of Contents
- [Technologies Used](#technologies-used)
- [Architecture and Design](#architecture-and-design)
- [Implementation Steps](#implementation-steps)
- [CI/CD Pipeline Setup](#cicd-pipeline-setup)
- [Security and Networking](#security-and-networking)
- [Testing and Validation](#testing-and-validation)
- [Final Adjustments and Scaling](#final-adjustments-and-scaling)
- [Project Outcomes](#project-outcomes)

## Technologies Used
- **AWS Services:** AWS Cloud9, ECS, ECR, CodeCommit, CodeDeploy, CodePipeline, RDS, S3, ALB.
- **Containerization:** Docker for packaging microservices.
- **Infrastructure as Code (IaC):** ECS task definitions, AppSpec files.
- **CI/CD Tools:** AWS CodePipeline, CodeDeploy, CodeCommit.
- **Security Measures:** Security Groups, IAM roles, and ALB Target Groups.
- **Monitoring & Logging:** AWS CloudWatch and CloudTrail.

## Architecture and Design
The project is structured to break down a monolithic application into two microservices:
1. **Customer Microservice** - Handles customer-related operations.
2. **Employee Microservice** - Manages employee-specific functions.

These microservices are deployed in AWS ECS and interact via an Application Load Balancer (ALB). A CI/CD pipeline automates their deployment and updates.

## Implementation Steps
1. **Planning and Cost Estimation:**
   - Designed an architecture diagram.
   - Estimated AWS service costs.

2. **Monolithic Application Analysis:**
   - Tested application functionality and performance.
   - Identified segments to split into microservices.

3. **Development Environment Setup:**
   - Configured AWS Cloud9 IDE.
   - Set up Git repositories in AWS CodeCommit.

4. **Microservices Development & Dockerization:**
   - Created separate directories for microservices.
   - Developed Dockerfiles and built/tested images.

5. **ECS Deployment Configuration:**
   - Created ECR repositories and stored Docker images.
   - Defined ECS task definitions and registered services.
   - Configured an Application Load Balancer (ALB) for routing.

## CI/CD Pipeline Setup
1. **Source Control:** Used AWS CodeCommit for version control.
2. **Build and Deployment:**
   - Configured AWS CodePipeline to automate build, test, and deploy phases.
   - Used CodeDeploy with AppSpec files for seamless deployment.
3. **Testing and Validation:**
   - Conducted pipeline tests to ensure functionality.
   - Deployed services to ECS and tested accessibility.

## Security and Networking
- Configured security groups to manage access control.
- Created target groups to route microservice traffic efficiently.
- Implemented IAM policies for secure access management.

## Testing and Validation
- Tested individual microservices for functionality and load performance.
- Verified CI/CD pipelines to ensure correct deployments.
- Validated ALB routing to microservices.

## Final Adjustments and Scaling
- Applied auto-scaling to customer microservice for traffic handling.
- Restricted access to employee microservice for security compliance.
- Updated UI and tested deployment pipelines for accuracy.

## Project Outcomes
- Successfully transitioned from a monolithic to a microservices architecture.
- Implemented a robust, automated CI/CD pipeline.
- Achieved improved scalability, reliability, and maintainability.
- Validated microservice communication and traffic management via ALB.

This project demonstrates expertise in AWS services, microservices deployment, and DevOps practices.

