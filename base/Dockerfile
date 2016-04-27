FROM centos:6.7

EXPOSE 3306 

ENV TERM=xterm

RUN yum -y update \
		&& yum -y install epel-release \
		&& yum -y install ansible which tar lsof wget git rsyslog\
		&& yum clean all
