ARG RELEASE=latest

FROM ubuntu:${RELEASE}

MAINTAINER borisskert <boris.skert@gmail.com>

ENV DEBIAN_FRONTEND	noninteractive

RUN apt-get update && \
    apt-get install -y python3 \
                       python3-pip \
                       python3-dev \
                       sudo && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/* && \
    pip3 install --upgrade pip

ENV SHELL /bin/bash
