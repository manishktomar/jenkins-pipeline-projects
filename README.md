# Jenkins Project

This project demonstrates automated Java web application deployment using Jenkins, Docker, and multi-job pipeline triggering for seamless code deployment.

## Project Overview

1. **Web Server Setup Using Docker for Java Code Deployment on Container**
   - A Docker-based setup for deploying Java applications on a Tomcat server container.
   - Jenkins is used to automate the process of building, creating, and deploying the Docker container.
   - Includes steps to integrate a Dockerfile, automate the building of a Docker image, and deploy the web application (WAR file) onto a running container.

2. **Multi-Job Triggering Pipeline for Code Deployment**
   - A Jenkins pipeline is configured to trigger sequential jobs automatically.
   - The pipeline triggers a second deployment job based on the successful completion of the first, ensuring streamlined deployment processes.
   - Utilizes Jenkins declarative pipeline syntax for job orchestration, allowing easier visualization and management of the deployment workflow.

## Project Details

### Prerequisites
- **Jenkins**: Installed with Docker and Pipeline plugins.
- **Docker**: Installed on the Jenkins server to build and manage containers.
- **Maven**: Used for building Java applications.
- **Git**: For version control and pulling code from the repository.
