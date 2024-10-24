
# Myrmidon

### Overview

Mymidon is one of the serveral repositories with Docker container configurations. All these repositories are one of my big personal projects to reduce the time of the configuration process of making a Docker container.

>**Note**: I will not be supporting this repository or any others; you are free to download it and use it as is, but if it does not work for you, I am not responsible in any way for it.

This repository have all the configurations you need, including a DB image of `PostgreSQL` in your container to work in a development environment.

This container is ready to work with:
- Python 3.9
- Django 4.2
- Django REST Framework 3.15
- Psycopg2 2.8

> **Note**: You can add other libraries of Python to work with, but you have to include them in `requirements.txt`. Make sure the new libraries are compatible with those that are by default.





### Requirements

- Docker 27.2.0
- Docker Hub Account


### Installation

Type `git clone` to get this repository.
```bash
$ git clone https://github.com/Nohua/myrmidon.git
```

After that, use docker build.
```bash
$ docker compose build
```

and run the container with `up`
```bash
$ docker compose up
```
