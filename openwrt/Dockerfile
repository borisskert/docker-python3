ARG OPENWRT_RELEASE=latest

FROM openwrtorg/rootfs:${OPENWRT_RELEASE}

MAINTAINER borisskert <boris.skert@gmail.com>

RUN mkdir /var/lock && \
    opkg update && \
    opkg install python3 \
                 python3-pip \
                 bash

RUN pip3 install --upgrade pip
