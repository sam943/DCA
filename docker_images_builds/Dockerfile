#simple server
FROM centos:latest
LABEL maintainer="c"

RUN yum install -y httpd
RUN echo "Our Container Website" >> /var/www/html/index.html

EXPOSE 80

ENTRYPOINT apachectl -DFOREGROUND
