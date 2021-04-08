# jenkins_CICDpipeline_docker

This video covers, CI & CD of docker based application using Jenkins Pipeline scripts (Groovy DSL)
stages: 
git clone 
maven build and creating a war package in target folder
we have a  dockerfile which copies target/war to tomcats folder
create/build a docker image called athi9419/my-app:2.0.0 using Dockerfile in current directory (note '.' at end of the docker build command)
push the image to docker hub
deploy the image in a web server like tomcat or ec2 server. here we have used ec2 server for deployment.
