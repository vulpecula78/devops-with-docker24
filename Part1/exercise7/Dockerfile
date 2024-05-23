#Exercise 7 Dockerfile
FROM ubuntu:22.04

#Set workdir
WORKDIR /usr/src/app

#Copy script into container
COPY script.sh .

#install curl
RUN apt update
RUN apt install -y curl

#When running docker run the command will be ./script.sh
CMD ./script.sh
