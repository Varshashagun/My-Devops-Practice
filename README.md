# My-Devops-Practice

How to install Jenkins Through Docker
Commands:
docker pull jenkins
docker pull jenkins/jenkins
docker run -d --name jenkins-server-docker jenkins/jenkins:latest
docker ps
docker run -d --name jenkins-server-docker -p 8080:8080  jenkins/jenkins:latest      #-p is used to expose the port so that docker can communicate with external systems

