# Fedora 28 docker base image with systemd [![Build Status](https://travis-ci.org/joramk/fc28-base.svg?branch=master)](https://travis-ci.org/joramk/fc28-base)
- Fedora 28 base system
- Full systemd support

## Docker run
~~~
docker run -d --tmpfs /run --tmpfs /tmp \
    -v /sys/fs/cgroup:/sys/fs/cgroup:ro \
    joramk/fc28-base:latest
~~~
