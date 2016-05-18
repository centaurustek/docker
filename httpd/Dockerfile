FROM centos:latest
RUN yum -y update && yum clean all
RUN yum -y install httpd && yum clean all
EXPOSE 80

ADD start.sh /start.sh
RUN chmod -v +x /start.sh

CMD ["/start.sh"]
