# TF2 on Raspberry Pi 4

The following are notes from setting up TF2 on my Raspberry Pi 4.
The goal is a simple setup for learning TensorFlow 2 and some related libraries.

All of this was done over VNC from my 10.5" iPad Pro.

## Docker setup

Docker installation was straightforward following the first bit of [these notes](https://www.raspberrypi.org/blog/docker-comes-to-raspberry-pi/).
All we have to do is install Docker using the provided script and reboot.

```
$ curl -sSL https://get.docker.com | sh
$ sudo halt
```

## TensorFlow setup

```
$ docker pull tensorflow/tensorflow:latest-py3-jupyter
...
Digest: sha256:37709ed9fcb2e57132710d521b5a6f826bc022e9f137750cc19728a1533f08e1
Status: Downloaded newer image for tensorflow/tensorflow:latest-py3-jupyter
docker.io/tensorflow/tensorflow:latest-py3-jupyter
```
