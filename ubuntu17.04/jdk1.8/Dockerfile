FROM kutuni/ubuntu:17.04

MAINTAINER kutuni

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update -y \
    && apt-get -y install openjdk-8-jre  --no-install-recommends \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

ENV JAVA_HOME /usr/lib/jvm/java-8-openjdk-amd64
