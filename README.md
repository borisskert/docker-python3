# python3 Docker images

These images can be used during ansible molecule tests.

## Included packages

* python3
* python3-pip

## Version overview

| Image version | Base image        | Python3 version | OS version   | CPU architecture                     |
|---------------|-------------------|-----------------|--------------|--------------------------------------|
| `noble`       | `ubuntu:noble`    | 3.12            | Ubuntu 24.04 | amd64, arm/v7, arm64/v8              |
| `jammy`       | `ubuntu:jammy`    | 3.10            | Ubuntu 22.04 | amd64, arm/v7, arm64/v8              |
| `focal`       | `ubuntu:focal`    | 3.8             | Ubuntu 20.04 | amd64, arm/v7, arm64/v8              |
| `bionic`      | `ubuntu:bionic`   | 3.6             | Ubuntu 18.04 | 386, amd64, arm/v7, arm64/v8         |
| `xenial`      | `ubuntu:xenial`   | 3.5             | Ubuntu 16.04 | 386, amd64, arm/v7, arm64/v8         |
| `bookworm`    | `ubuntu:bookworm` | 3.11            | Debian 12    | 386, amd64, arm/v5, arm/v7, arm64/v8 |
| `bullseye`    | `ubuntu:bullseye` | 3.9             | Debian 11    | 386, amd64, arm/v5, arm/v7, arm64/v8 |
| `buster`      | `ubuntu:buster`   | 3.7             | Debian 10    | 386, amd64, arm/v7, arm64/v8         |

## License

MIT

## Author Information

* [borisskert](https://github.com/borisskert)

## Further links

* [borisskert/python3 @ Docker hub](https://hub.docker.com/r/borisskert/python3)
* [borisskert/python3 @ Github](https://github.com/borisskert/docker-python3)
* [pycontribs Docker images](https://hub.docker.com/u/pycontribs)
