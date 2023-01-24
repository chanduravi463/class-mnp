FROM centos:7
RUN yum install httpd -y
COPY index.html /var/www/html/
EXPOSE 80
ENV user = Ravi
ENTRYPOINT ["/bin/bash", "-c", "httpd && bash"]

