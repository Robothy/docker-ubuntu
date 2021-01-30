# docker-ubuntu

This repository contains some scripts to build a Docker ubuntu image with several common used tools.

The official ubuntu image has the minimum tool collection, which exclude some software, such as `ping`, that is necessary for a developer.   
This ubuntu image will pre-install some tools to empower the official image.

## Usage

### pull this image from Docker Hub

This 

```shell
docker run --name ubuntu luofuxiang/ubuntu
```

### Build the image in your local computer

## TODO

+ Set domestic source mirrors

+ Pre-Install below tools
    - wget
    - iputils-ping
    - net-tools
    - iproute2