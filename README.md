# python3 Docker images

These images can be used during ansible molecule tests.

## Included packages

* python3
* python3-pip (upgraded to latest version)
* python3-dev (and all dependencies)
* sudo

## Version overview

| Image version | Base image | Python3 version | OS version |
|---------------|------------|-----------------|------------|
| `focal`       | `ubuntu:focal` | 3.8.2       | Ubuntu 20.04 |
| `bionic`      | `ubuntu:bionic` | 3.6.9      | Ubuntu 18.04 |
| `xenial`      | `ubuntu:xenial` | 3.5.2      | Ubuntu 16.04 |
| `buster`      | `ubuntu:buster` | 3.7.3      | Debian 10    |
| `stretch`     | `ubuntu:stretch` | 3.5.3     | Debian 9     |
| `jessie`      | `ubuntu:jessie`  | 3.4.2     | Debian 8     |
