FROM ubuntu:16.04

WORKDIR /usr/app
RUN apt-get update
RUN apt-get -y install curl
COPY . .
RUN chmod +x ./start.sh
CMD ./start.sh
