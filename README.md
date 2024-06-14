# deploymement-pipeline-jenkins-aws_eks
jenkinsapp pipeline deployment to aws elastic kubernetes service

# jenkins-pipeline-deploy-to-eks
# Project Name: This project demonstrates the overall picture of the jenkinsapp deployment into k8s using entirely the power of Jenkins CI/CD Pipeline workflow
# project steps and workflow

## 1. First using the local key pair and the security droup was confisgured,Vpc andd route table done
## 2. The provisoning of the jenkins Server  was done using terraform IAC with all the dependencies, libraries aneeded yes.
## 2. Acceessiblity to the jenkins server was done with the usual set up the server was accessed on port 880 already enabled in the secuirty group
# Logging into the jenkins server was done with the username and password gieven to the admin during installation.
## 4. However to create the K8s Cluster, creating the deployments.yaml and Services.yaml file use the jekins-pipeline-to-eks in the jenkinsfile 
## 5. Finally,test if the jenkisapp works and is running 
## 6. Please do remeemeber to Destroy the infrastructure, if forgoten you will be charged by AWS
