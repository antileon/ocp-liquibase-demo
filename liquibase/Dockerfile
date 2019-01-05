FROM centos:7

MAINTAINER Udo Urbantschitsch <udo@redhat.com>

RUN yum install epel-release java -y && \
    yum install liquibase postgresql-jdbc -y && \
    yum clean all

ENTRYPOINT liquibase
