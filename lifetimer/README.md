# Application

Simple page application to calculate life timer based on statistic data

![Alt text](screenshot.png?raw=true "Diagram Image")

# Docker Hub

Repository [link](https://hub.docker.com/repositories/estanqueiroa)

# Docker Image Information

* Base image: nginx:alpine
* Exposed port: 80
* Image size: ~45MB
* Repository: docker.io/estanqueiroa/lifetimer

# Docker Build

Run this command `docker build -t estanqueiroa/lifetimer .`

# Quick Start

Run this command `docker run -d -p 8081:80 estanqueiroa/lifetimer:latest`

Then visit http://localhost:8081⁠ in your browser.
