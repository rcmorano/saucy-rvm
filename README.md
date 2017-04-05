![build passing](https://img.shields.io/docker/automated/rcmorano/ubuntu-rvm.svg)

# What you get

A ready to use ubuntu-rvm-ruby container (in different flavours) to use as base image for your development containers.

# How to use

You can just pull the image from the official 'docker' index since it's a trusted build linked with github 'Dockerfile' in this repo:
```
docker pull rcmorano/saucy-rvm
docker pull rcmorano/precise-rvm
docker pull rcmorano/trusty-rvm
docker pull rcmorano/ubuntu-rvm:xenial
```

Or you can build the image yourself:
```
git clone https://github.com/rcmorano/ubuntu-rvm.git
git checkout xenial
docker build -t rcmorano/ubuntu-rvm:xenial ubuntu-rvm/
```

You'll get a ruby-head-able interactive container for messing up with some gemsets:

```
docker run -t -i rcmorano/ubuntu-rvm:xenial
```

# Supported versions

There will be a branch of this repo for each Ubuntu version. Just take a look at the current branches :]
