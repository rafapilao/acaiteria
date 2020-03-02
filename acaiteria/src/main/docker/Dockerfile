FROM openjdk:8-jdk-alpine

MAINTAINER Rafael Alves <rafaell.alves.dev@gmail.com>

RUN mkdir -p /usr/local/acaiteria

ADD @project.build.finalName@.jar /usr/local/acaiteria/

RUN mkdir -p /usr/local/dockerize
 
ADD @project.build.finalName@.jar /usr/local/acaiteria/

ADD run.sh run.sh

RUN chmod +x run.sh

CMD ./run.sh
