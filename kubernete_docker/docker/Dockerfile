FROM ubuntu:22.04

RUN apt update
RUN apt install nginx -y
RUN echo 'hello word' > /var/www/html/index.html

EXPOSE 80

CMD nginx -g 'daemon off;'
