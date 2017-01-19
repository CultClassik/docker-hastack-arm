# docker-home-stack

This repository contains a collection of Docker containers for media downloading and management as well as home automation.

### Containers:
* Mosquitto
* Home-Assistant
* Muximux
* Kodi Headless
* Sonarr
* Couch Potato
* RUTorrent
* FireTV Server
* Portainer
* OpenVPN
* Nginx Reverse Proxy

Requires MySQL database and NZBGet, these are run on my QNAP NAS device.

The Docker host needs to have several NFS shares mapped to provide data stores for the containers to persist data.
