# VERSION 1.0

FROM gothug/jdk-oracle

MAINTAINER Vasily Kozhukhovskiy

### Install Firefox & XVfb
RUN     echo "deb http://archive.ubuntu.com/ubuntu precise main universe" >> /etc/apt/sources.list
RUN     apt-get update
RUN     apt-get install -y firefox xvfb

ADD xvfb.sv.conf /etc/supervisor/conf.d/
