FROM node:latest

RUN apt-get update \
    && apt-get install -y vim procps net-tools \
    && apt-get clean ;

WORKDIR /app/front/cake-front