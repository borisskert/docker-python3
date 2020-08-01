ARG CENTOS_RELEASE=latest

FROM centos:${CENTOS_RELEASE}

MAINTAINER borisskert <boris.skert@gmail.com>

ARG PYTHON_VERSION
ENV PYTHON_VERSION ${PYTHON_VERSION:-3}

ARG TARGETPLATFORM
ARG BUILDPLATFORM

# https://github.com/multiarch/centos/issues/1#issuecomment-511644471
RUN if [ "${TARGETPLATFORM}" == "linux/arm/v7" ]; then \
        echo "armhfp" > /etc/yum/vars/basearch; \
        echo "armv7hl" > /etc/yum/vars/arch; \
        echo "armv7hl-redhat-linux-gpu" > /etc/rpm/platform; \
    fi; \
    yum update -y && \
    yum install -y python${PYTHON_VERSION} && \
    yum clean all && \
    pip3 install --upgrade pip

ENV SHELL /bin/bash
