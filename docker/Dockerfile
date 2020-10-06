# getting base image ubuntu 
FROM ubuntu:18.04
MAINTAINER Sai Krishna <sknarsingrao@qwinix.io>
RUN apt-get update
RUN apt-get install -y nginx
COPY sample.html /var/www/html/index.html
EXPOSE 80
CMD ["nginx","-g","daemon off;"]