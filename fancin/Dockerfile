FROM nginx:alpine
MAINTAINER Camille Baronnet <git@camillebaronnet.fr>

RUN apk update && apk add nginx-mod-http-fancyindex && rm -rf /var/cache/apk/*

ADD nginx.conf /etc/nginx/nginx.conf
ADD www /var/www
