![Docker Compose UI](https://raw.githubusercontent.com/francescou/docker-compose-ui/master/static/images/logo-dark.png)

[![Docker Stars](https://img.shields.io/docker/stars/francescou/docker-compose-ui.svg)](https://hub.docker.com/r/francescou/docker-compose-ui/)
[![Docker Pulls](https://img.shields.io/docker/pulls/francescou/docker-compose-ui.svg)](https://hub.docker.com/r/francescou/docker-compose-ui/)

## What is it

Docker Compose UI is a web interface for Docker Compose.

The aim of this project is to provide a minimal HTTP API on top of Docker Compose while maintaining full interoperability with Docker Compose CLI.

The application can be deployed as a single container, there are no dependencies nor databases to install.

## Install docker-compose-ui

docker-compose build -t dccomposeui01 .

## Run with docker-compose

docker-compose up -d

## Run with swarm

docker stack deploy -c docker-compose.yml dccomposeui01




