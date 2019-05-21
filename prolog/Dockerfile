FROM ubuntu:latest

RUN apt update && apt install -y software-properties-common

RUN apt-add-repository ppa:swi-prolog/stable && apt update && apt install -y swi-prolog wget

RUN wget https://github.com/exercism/cli/releases/download/v3.0.11/exercism-linux-64bit.tgz

RUN tar -xf exercism-linux-64bit.tgz

RUN mv exercism /bin

RUN mkdir -p /root/exercism && mkdir -p /root/.config/exercism

WORKDIR /root/exercism
