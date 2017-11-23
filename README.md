# Introduction

This is a docker image with the conjur-cli pre installed


# conjur-cli

Command-line interface for Conjur.

*NOTE*: Conjur v4 users should use the `v5.x.x` release path. Conjur CLI `v6.0.0` only supports Conjur v5 and newer.

A complete reference guide is available at [conjur.org](https://www.conjur.org).

## Docker images

[![Docker Build Status](https://img.shields.io/badge/docker%20buuild-passing-brightgreen.svg)](https://hub.docker.com/r/denyall/conjur-cli/)

Images for development/experimental use are automatically built [on docker hub](https://hub.docker.com/r/denyall/conjur-cli/).
These are based off [Dockerfile.standalone](Dockerfile.standalone) and can be rebuilt with:


Note these images are not subject to any QA at the moment and so should never be used in production, especially without specific image id pin.



## Quick start



```
docker run -it --rm denyall/conjur-cli:latest
```



