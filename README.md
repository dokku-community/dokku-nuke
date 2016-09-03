# dokku-nuke [![Build Status](https://img.shields.io/travis/josegonzalez/dokku-nuke.svg?branch=master "Build Status")](https://travis-ci.org/josegonzalez/dokku-nuke)

Stop all running containers, then delete all containers and images.

## requirements

- dokku 0.4.0+
- docker 1.8.x

## installation

```shell
# on 0.4.x
dokku plugin:install https://github.com/josegonzalez/dokku-nuke.git nuke
```

## usage

Stop all running containers, then delete all containers and images.

```shell
dokku nuke
```

*WARNING*: This will wipe ALL of your Docker containers and images!
