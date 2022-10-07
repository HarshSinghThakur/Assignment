FROM ubuntu:18.04
MAINTAINER Harsh-Singh-Thakur
RUN apt update -y && apt install apache2 vim -y
RUN echo "<h1> Docker Ubuntu-apache Assignment </h1>" > /var/www/html/index.html
CMD /usr/sbin/apache2ctl -D FOREGROUND

