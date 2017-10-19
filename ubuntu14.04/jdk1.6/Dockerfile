FROM kutuni/ubuntu:14.04

MAINTAINER kutuni

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update \
 && apt-get install -y -f openjdk-6-jre --no-install-recommends \
 && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

ENV JAVA_HOME /usr/lib/jvm/java-6-openjdk-amd64



