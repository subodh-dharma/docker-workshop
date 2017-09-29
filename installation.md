# Installation

Don't Worry you can install Docker on all OS. Choose yours....

## The Hard Way

On any \*nix systems.

```
curl -sSL https://get.docker.com/ | sh
```
After installation execute the following, so that you don't need to execute the it using `sudo`

```
sudo groupadd docker
sudo gpasswd -a $USER docker
newgrp docker
```

## From the Docker Community Edition

* [Ubuntu](https://store.docker.com/editions/community/docker-ce-server-ubuntu)
* [Windows](https://store.docker.com/editions/community/docker-ce-desktop-windows)
* [Mac](https://store.docker.com/editions/community/docker-ce-desktop-mac)
* [Fedora](https://store.docker.com/editions/community/docker-ce-server-fedora)
