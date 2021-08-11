FROM ubuntu:18.04

RUN apt-get update && apt-get -y install curl

WORKDIR /usr/src/app

COPY curl.sh . 

RUN chmod +x curl.sh

cmd ./curl.sh
