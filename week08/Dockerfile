FROM centos:latest
RUN yum -y install httpd
COPY index.html apiit.jpeg /var/www/html/
ENTRYPOINT ["/usr/sbin/httpd", "-D", "FOREGROUND"]
EXPOSE 80

