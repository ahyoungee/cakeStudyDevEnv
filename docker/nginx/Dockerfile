FROM nginx:latest

RUN apt-get update \
 && apt-get install -y vim procps net-tools

COPY ./etc/nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf