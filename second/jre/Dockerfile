#
# MAINTAINER        Carson,C.J.Zeong <zcy@nicescale.com>
# DOCKER-VERSION    1.6.2
#
# Dockerizing jre: Dockerfile for building jre images
#
FROM       csphere/centos
MAINTAINER Carson,C.J.Zeong <zcy@nicescale.com>

ENV JAVA_VERSION 1.8.0
ENV JRE_HOME /usr/lib/jvm/jre

# Install jre
RUN yum -y install java-${JAVA_VERSION}-openjdk mysql && \
    yum clean all
