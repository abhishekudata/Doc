
FROM ubuntu:16.04
WORKDIR /home/bhushan/Downloads/OSS Final/jdk_ubuntu
MAINTAINER bhushan kalode
RUN apt-get update 
RUN apt install default-jre -y
RUN apt install default-jdk -y
COPY . .
RUN javac Hello.java  
CMD ["java", "Hello"]  

