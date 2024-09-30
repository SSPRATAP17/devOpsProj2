# Edureka Devops Certification Project 2

## Problem Statement 

A retail company Abstergo Corp.has recently setup an online shopping portal(website) to sell their products. Due to fierce competition, the company wants a solution that can reduce the time and effort it needs to enhance the functionality of their website on a regular basis. They are looking for an automated way to deploy the new code (for new features) to production website whenever they want.

### Business Requirements
- The team of developers working on new features will merge their code to a GitHub repo.
- As soon as the code reaches GitHub, using a CI (Continuous Integration) pipeline, setup in Jenkins, automated builds will be triggered.
- The automated builds will frequently deploy new features to the production website.
- Every build will prepare a Dockerfile and push docker images to docker-hub.
- Every docker image will be deployed (Continuous Deployment) to a kubernetes-cluster

#### Forked Repository for Project 
This Project is based on a sample project repository forked from [Edureka's Devops Certification Sample Repo](https://github.com/bhavukm/cicd-pipeline-train-schedule-autodeploy)
