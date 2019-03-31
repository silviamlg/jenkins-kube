FROM ubuntu:latest
RUN apt-get -yqq update; apt-get -yqq install nginx;
RUN echo "DEMO-JENKINS quinta versione" > /var/www/html/index.html
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
EXPOSE 80
