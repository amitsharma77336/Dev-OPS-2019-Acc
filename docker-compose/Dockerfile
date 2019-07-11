#select base image
FROM ubuntu:16.04

#owner
MAINTAINER Amit Sharma <amit@gmail.com>

# Update Ubuntu Repo 
RUN apt-get update
COPY spring-boot-sample-atmosphere-1.4.0.BUILD-SNAPSHOT.jar /atmos.jar
# Install apache
RUN apt-get install apache2 -y
RUN apt-get install openjdk-8-jdk -y

CMD java -jar /atmos.jar


# Add Custom page to container
#COPY helloworld.html /var/www/html/hello.html

#RUN service of apache

#CMD ["/usr/sbin/apache2ctl","-D","FOREGROUND"]


