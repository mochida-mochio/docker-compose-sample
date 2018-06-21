FROM amazonlinux:latest

# Install PHP5.6 & Apache
RUN yum install php php-mysql mysql -y

# Clear yum cache
RUN yum clean all

# for web
EXPOSE 80

CMD /usr/sbin/httpd -DFOREGROUND