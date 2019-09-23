FROM zacktymphany/docker-test:latest

USER root

WORKDIR /home

ADD https://github.com/ZackTymphany/docker-test.git ./

RUN apt-get update && apt-get install tree

RUN touch zack-test2.txt

ENV SHELL=/bin/bash
