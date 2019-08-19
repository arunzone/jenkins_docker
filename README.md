# jenkins_docker
ci with jenkins using docker

## Easy start (Autoinstall plugins)
Install default plugins
default admin user as env for up and running for dev

Handy commands:  
docker build -t jenkins-master .  
docker run -d -p 49001:8080 -v $HOME/jenkins_home:/var/jenkins_home --name jenkins-master jenkins-master  
docker rm -f jenkins-master  
