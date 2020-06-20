# python3 Docker images

These images can be used during ansible molecule tests.

## Included packages

* python3
* python3-pip (upgraded to latest version)
* python3-dev (and all dependencies)
* sudo

## Version overview

| Image version | Base image | Python3 version | OS version | CPU architecture |
|---------------|------------|-----------------|------------|------------------|
| `focal`       | `ubuntu:focal` | 3.8.2       | Ubuntu 20.04 | amd64, arm/v7 arm64 |
| `bionic`      | `ubuntu:bionic` | 3.6.9      | Ubuntu 18.04 | 386, amd64, arm/v7, arm64 |
| `xenial`      | `ubuntu:xenial` | 3.5.2      | Ubuntu 16.04 | 386, amd64, arm/v7, arm64 |
| `buster`      | `ubuntu:buster` | 3.7.3      | Debian 10    | 386, amd64, arm/v7, arm64 |
| `stretch`     | `ubuntu:stretch` | 3.5.3     | Debian 9     | 386, amd64, arm/v7, arm64 |
| `jessie`      | `ubuntu:jessie`  | 3.4.2     | Debian 8     | 386, amd64, arm/v7 |

## License

MIT

## Author Information

* [borisskert](https://github.com/borisskert)

## Further links

* [borisskert/python3 @ Docker hub](https://hub.docker.com/r/borisskert/python3)
* [borisskert/python3 @ Github](https://github.com/borisskert/docker-python3)
* [pycontribs Docker images](https://hub.docker.com/u/pycontribs)
