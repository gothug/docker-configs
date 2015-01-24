# VERSION 1.0

FROM gothug/jdk-oracle #(jdk 7, built using this Docker file: https://github.com/Krijger/docker-cookbooks/blob/master/jdk7-oracle/Dockerfile)


MAINTAINER Vasily Kozhukhovskiy

### Install Firefox & XVfb
RUN     echo "deb http://archive.ubuntu.com/ubuntu precise main universe" >> /etc/apt/sources.list
RUN     apt-get update
RUN     apt-get install -y firefox xvfb

ADD xvfb.sv.conf /etc/supervisor/conf.d/
