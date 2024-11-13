# Project Title
**Device-Monitoring-web-app**

This is a simple web application that allows you to monitor the **memory** and **CPU usage** of a machine.

## Key Technologies
- **Python**: Used as the base programming language.
- **Docker**: Containerizes the application and manages all necessary dependencies.
- **Amazon EKS**: Deploys the Docker image on Amazon's Elastic Kubernetes Service.
- **Kubernetes**: Manages container orchestration and optimizes application deployment.

## Files and Structure

### requirements.txt
Contains all the necessary Python modules required to run the application.

### Docker
The Docker setup includes all dependencies and resources needed to build and deploy the web application as a container.

### EKS
Amazon EKS is used to add the Docker image, which allows us to define a Kubernetes deployment for scaling, managing and hosting.

### Kubernetes
Kubernetes handles the **container orchestration** to optimize deployment, scaling, and management of the application on Amazon EKS.
