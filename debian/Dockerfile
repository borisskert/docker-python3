ARG RELEASE=latest

FROM debian:${RELEASE}

MAINTAINER borisskert <boris.skert@gmail.com>

ENV DEBIAN_FRONTEND	noninteractive

RUN apt-get update && \
    apt-get install -y \
                       pkg-config \
                       python3 \
                       python3-pip \
                       python3-dev \
                       sudo && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/* && \
    rm -f /usr/lib/python3.11/EXTERNALLY-MANAGED && \
    python3 -m pip install --upgrade pip

ENV SHELL /bin/bash
