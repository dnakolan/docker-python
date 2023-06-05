# docker-python
Iterating on the docker-python language guide

[![All Contributors](https://img.shields.io/github/contributors/dnakolan/docker-python)](#contributors-)
![Issues](https://img.shields.io/github/issues/dnakolan/docker-python)
![Pull Requests](https://img.shields.io/github/issues-pr/dnakolan/docker-python?)
![Forks](https://img.shields.io/github/forks/dnakolan/docker-python)
![Stars](https://img.shields.io/github/stars/dnakolan/docker-python)
![License](https://img.shields.io/github/license/dnakolan/docker-python)

A project I'm working on to hone my python developmen skills. This is based on the public tutorial on
this [website](https://docs.docker.com/language/python/)

# Requirements
Python must be installed on your local machine. You must also have docker cli and a docker daemon
running on your local machine to build and run these images as per the tutorial linked above.

# How to build
    ```bash
    cd docker-python/
    docker build --tag docker-python .
    ```

# How to run after building
    ```bash
    docker compose -f docker-compose-dev.yml up --build
    ```
