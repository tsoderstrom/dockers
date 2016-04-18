FROM centos:6.7

EXPOSE 3306 

ENV TERM=xterm

RUN yum -y update \
		&& yum -y install epel-release \
		&& yum -y install ansible which tar lsof git rsyslog\
		&& yum -y install http://www.percona.com/downloads/percona-release/redhat/0.1-3/percona-release-0.1-3.noarch.rpm \
		&& yum -y install Percona-Server-server-56 \
		&& yum clean all
