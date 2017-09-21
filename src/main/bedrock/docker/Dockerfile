FROM docker.br.hmheng.io/base-ubuntu:java_1.8.0_74-b02
EXPOSE 8080
MAINTAINER Maksim Karvonen

ADD target/spring-boot-bedrock-0.1.0-SNAPSHOT.jar /opt/hmh/demo/hello-world.jar
WORKDIR /opt/hmh/demo

CMD java -jar hello-world.jar
