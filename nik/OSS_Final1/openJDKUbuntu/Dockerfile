# Ubuntu 15.04 with Java 8 installed.

# Build image with:  docker build -t krizsan/ubuntu1504java8:v1 .

FROM ubuntu:15.04

MAINTAINER Ivan Krizsan, https://github.com/krizsan

RUN apt-get update && \

    apt-get upgrade -y && \

    apt-get install -y  software-properties-common && \

    add-apt-repository ppa:webupd8team/java -y && \

    apt-get update && \

    echo oracle-java7-installer shared/accepted-oracle-license-v1-1 select true | /usr/bin/debconf-set-selections && \

    apt-get install -y oracle-java8-installer && \

    apt-get clean
