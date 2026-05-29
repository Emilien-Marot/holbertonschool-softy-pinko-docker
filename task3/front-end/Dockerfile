FROM nginx:latest

RUN apt-get update
RUN apt-get upgrade -y

COPY ./softy-pinko-front-end /var/www/html/softy-pinko-front-end
COPY ./softy-pinko-front-end.conf /etc/nginx/conf.d/default.conf
