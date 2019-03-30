FROM ubuntu:latest
RUN apt-get -yqq update; apt-get -yqq install nginx;
RUN echo "DEMO-JENKINS prima fase" > /var/www/html/index.html
#CMD ["/usr/sbin/nginx -g" "daemon off;"]
#CMD ["ls -la /usr/sbin/nginx"]
ENTRYPOINT ["/usr/sbin/nginx", "-g", "daemon off;"]
EXPOSE 80
