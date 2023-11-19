# python3 Docker images

These images can be used during ansible molecule tests.

## Included packages

* python3
* python3-pip (upgraded to latest version)

## Version overview

| Image version | Base image                  | Python3 version | OS version   | CPU architecture                     |
|---------------|-----------------------------|-----------------|--------------|--------------------------------------|
| `jammy`       | `ubuntu:jammy`              | 3.10.4          | Ubuntu 22.04 | amd64, arm/v7, arm64/v8              |
| `focal`       | `ubuntu:focal`              | 3.8.5           | Ubuntu 20.04 | amd64, arm/v7, arm64/v8              |
| `bionic`      | `ubuntu:bionic`             | 3.6.9           | Ubuntu 18.04 | 386, amd64, arm/v7, arm64/v8         |
| `xenial`      | `ubuntu:xenial`             | 3.5.2           | Ubuntu 16.04 | 386, amd64, arm/v7, arm64/v8         |
| `bookworm`    | `ubuntu:bookworm`           | 3.11.2          | Debian 12    | 386, amd64, arm/v5, arm/v7, arm64/v8 |
| `bullseye`    | `ubuntu:bullseye`           | 3.9.2           | Debian 11    | 386, amd64, arm/v5, arm/v7, arm64/v8 |
| `buster`      | `ubuntu:buster`             | 3.7.3           | Debian 10    | 386, amd64, arm/v7, arm64/v8         |

## License

MIT

## Author Information

* [borisskert](https://github.com/borisskert)

## Further links

* [borisskert/python3 @ Docker hub](https://hub.docker.com/r/borisskert/python3)
* [borisskert/python3 @ Github](https://github.com/borisskert/docker-python3)
* [pycontribs Docker images](https://hub.docker.com/u/pycontribs)
