# dokku-nuke [![Build Status](https://img.shields.io/travis/heichblatt/dokku-nuke.svg?branch=master "Build Status")](https://travis-ci.org/heichblatt/dokku-nuke)

Stop all running containers, then delete all containers and images.

## requirements

- dokku 0.4.0+
- docker 1.8.x

## installation

```shell
# on 0.3.x
cd /var/lib/dokku/plugins
git clone https://github.com/heichblatt/dokku-nuke.git nuke
dokku plugins-install

# on 0.4.x
dokku plugin:install https://github.com/heichblatt/dokku-nuke.git nuke
```

## usage

Stop all running containers, then delete all containers and images.

```bash
dokku nuke
```

*WARNING*: This will wipe ALL of your Docker containers and images!
