FROM zacktymphany/docker-test:latest

USER root

ADD https://github.com/ZackTymphany/docker-test.git /home

RUN apt-get update && apt-get install tree

RUN touch /home/zack-test1.txt

ENV SHELL=/bin/bash
