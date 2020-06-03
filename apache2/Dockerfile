FROM ubuntu:xenial
LABEL maintainer="tatianamoraru1998@gmail.com"
RUN apt-get update && apt-get install apache2 -y
EXPOSE 80
CMD ["/usr/sbin/apache2ctl", "-D", "FOREGROUND"]

