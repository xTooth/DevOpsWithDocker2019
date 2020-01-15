FROM ubuntu:16.04

WORKDIR /pythoneroos
RUN apt update -y
RUN apt install -y  python3 
RUN apt install -y python3-pip
RUN pip3 install --upgrade pip
RUN pip3 install Flask
RUN apt install -y sqlite3
RUN apt install -y nano
CMD /bin/bash

