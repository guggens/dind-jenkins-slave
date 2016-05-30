# dind-jenkins-slave
Docker in docker jenkins slave for use with docker plugin with jenkins 2.x

How to setup: 

- setup your docker to launch with remote api enabled, see http://stackoverflow.com/questions/18038985/how-to-connect-to-docker-api-from-another-machine/19758886#19758886

- start a new jenkins docker container from default docker image (https://hub.docker.com/r/jenkinsci/jenkins/) :
docker run -d jenkinsci/jenkins

- install docker plugin, see https://wiki.jenkins-ci.org/display/JENKINS/Docker+Plugin
- add a new cloud (Docker) 
- connect to docker remote api
- create a new image type
