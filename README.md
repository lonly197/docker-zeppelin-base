# docker-zeppelin-base

This is a basic [docker](https://www.docker.com/what-docker) image for building [docker-zeppelin](http://github.com/lonly197/docker-zeppelin) and [docker-zeppelin-cn](http://github.com/lonly197/docker-zeppelin-cn)

# Overview

- ![Version](https://images.microbadger.com/badges/version/xemuliam/zeppelin:0.7.3.svg) ![Layers](https://images.microbadger.com/badges/image/xemuliam/zeppelin-base:0.7.3.svg) __0.7.3  = latest__

- ![Version](https://images.microbadger.com/badges/version/xemuliam/zeppelin:0.7.2.svg) ![Layers](https://images.microbadger.com/badges/image/xemuliam/zeppelin-base:0.7.2.svg) __0.7.2__

- ![Docker builds](https://img.shields.io/docker/automated/xemuliam/zeppelin.svg) ![Docker Pulls](https://img.shields.io/docker/pulls/xemuliam/zeppelin.svg) ![Docker Stars](https://img.shields.io/docker/stars/xemuliam/zeppelin.svg)

# Exposed ports

- 8080 - Zeppelin web application port
- 8443 - Zeppelin web application secure port

# Volumes

All below volumes can be mounted to docker host machine folders or shared folders to easy maintain data inside them. 

Zeppelin-specific:
- /opt/zeppelin/conf
- /opt/zeppelin/logs
- /opt/zeppelin/notebook
- /opt/zeppelin/local-repo
- /opt/zeppelin/helium

# Contact me

- Email: <lonly197@qq.com>