# ITI Final Project

Deploy a python web application on GKE by CI/CD Pipeline. if you need to know more about app you can go and read this readme file https://github.com/atefhares/DevOps-Challenge-Demo-Code in short its python app depend on redis
#
### First Part: [ Infrastructure Repository ](https://github.com/MohamedArafa98/final-project-infrastructure)
### second part:
- dockerize python application
- configure Credentials in Jenkins
- create CI pipeline with Jenkins
- Create CD pipline with  Jenkins

# dockerize my app 
- [ Dockerfile ](https://github.com/MohamedArafa98/python-application-final/blob/main/Dockerfile)) 

# Add Credentials in Jenkins
 - github Credentials
 - dockerhub Credentials
 - serviceaccount Credentials

# create Continuous Integration CI pipline :
  -  pull code from github 
  -  build py-app image you can use (docker - buildah - kaniko - or anything else) to build your image
  -  push this image to dockerhub
  -  trigger CD pipline to run
  
# create CD Pipline
  - apply deployment application in K8s
