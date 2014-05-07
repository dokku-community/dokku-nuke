# dokku-list

Stop all running containers, then delete all containers and images.

## Installation

```bash
cd /var/lib/dokku/plugins
sudo git clone git@github.com:heichblatt/dokku-nuke.git nuke
```

## Usage

Stop all running containers, then delete all containers and images.
```bash
nuke
```

## Warning

This will wipe ALL of your Docker containers and images!
