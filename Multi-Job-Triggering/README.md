# Multi-Job Triggering Pipeline for Code Deployment

- A Jenkins pipeline is configured to trigger sequential jobs automatically.
- The pipeline triggers a second deployment job based on the successful completion of the first, ensuring streamlined deployment processes.
- Utilizes Jenkins declarative pipeline syntax for job orchestration, allowing easier visualization and management of the deployment workflow.

### Job A
1. Stage  : Checkout Code
2. Stage  : Build with Maven
3. Stage  : Docker Setup
4. Stage  : War Deploy to Tomcat Pipeline

### Job B
1. Stage  : War Deploy to Tomcat
2. Stage  : Display Container IP and Port
