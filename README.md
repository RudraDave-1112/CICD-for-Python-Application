# CICD-for-Python-Application
In this lab, I designed and implemented a Continuous Integration and Continuous Deployment (CI/CD) pipeline for a Python-based API. The automation included infrastructure provisioning, pipeline configuration using Jenkins, and deployment of the application via Ansible.

1. Set Up GitHub Repositories:
Forked and used three key repos:
JenkinsComplex: for configuring Jenkins pipelines.
ContinuousDelivery: for Ansible playbooks and app deployment logic.
ProvisionAppServer: for provisioning the target AWS EC2 app server.

2. Provisioned EC2 App Server:
Deployed an EC2 instance on AWS to host the Python API application.
Verified the instance was running and accessible for remote automation.

3. Configured CI Pipeline:
Built a Jenkins pipeline for Continuous Integration to build the Python API automatically on push.
Captured and reviewed successful pipeline build output.

4. Configured CD Pipeline:
Implemented a second Jenkins pipeline for Continuous Deployment.
This pipeline used Ansible to remotely deploy the built API to the provisioned EC2 instance.
Verified successful execution by checking the terminal output.

5. Validated Deployment:
Used terminal output to confirm that student data from the API was successfully listed.
Verified that the API was accessible and running on the server.

6.Captured Running AWS Infrastructure:
Documented the live state of all running AWS instances involved in the deployment.

