# TF2 on Raspberry Pi 4

The following are notes from setting up TF2 on my Raspberry Pi 4.
All of this was done over VNC from my 10.5" iPad Pro.

## Docker setup

Docker installation was straightforward following the first bit of [these notes](https://www.raspberrypi.org/blog/docker-comes-to-raspberry-pi/).
All we have to do is install Docker using the provided script and reboot.

```
$ curl -sSL https://get.docker.com | sh
$ sudo halt
```
