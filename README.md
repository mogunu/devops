# devops

Welcome to my repo


https://getintodevops.com/blog/the-simple-way-to-run-docker-in-docker-for-ci



 setenforce 0
 
 docker pull h1kkan/jenkins-docker:lts
 
 docker run -u root -p 8080:8080 -p 50000:50000 -v /var/jenkins_home/:/var/jenkins_home/ -v /var/run/docker.sock:/var/run/docker.sock h1kkan/jenkins-docker:lts
