FROM ubuntu
MAINTAINER anusha
LABEL name=anusha
RUN apt update / apt install openjdk:9 / apt install apache2
COPY index.html /var/www/html/index.html
EXPOSE 8080
CMD ["catalina.sh","run"]
## this is apache2 on ubuntu
