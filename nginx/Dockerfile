FROM ubuntu:xenial
LABEL maintainer="tatianamoraru1998@gmail.com"
RUN apt-get update && apt-get install nginx -y 
EXPOSE 80 443
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
