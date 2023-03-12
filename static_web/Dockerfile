# Version: 0.0.1

FROM ubuntu:18.04

MAINTAINER Markos Rendell "markosrendell@gmail.com"

RUN apt-get update

RUN apt-get install -y nginx

RUN echo 'Hi, I am in your container' \
> /usr/share/nginx/html/index.html

EXPOSE 80

VOLUME ["/opt/project"]

CMD ["/usr/sbin/nginx", "-g", "daemon off;"]

