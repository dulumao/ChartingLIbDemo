FROM debian:jessie

RUN apt-get update
RUN apt-get install apache2 -y
WORKDIR /var/www/html/
ADD . ./
EXPOSE 80
CMD /usr/sbin/apache2ctl -D FOREGROUND