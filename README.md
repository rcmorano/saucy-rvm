# How to use

You can just pull the image from the official 'docker' index since it's a trusted build linked with github 'Dockerfile' in this repo:
```
docker pull rcmorano/ubuntu-rvm:saucy
docker pull rcmorano/ubuntu-rvm:precise
```

Or you can build the image yourself:
```
git clone https://github.com/rcmorano/ubuntu-rvm.git
git checkout saucy
docker build -t rcmorano/ubuntu-rvm:saucy ubuntu-rvm/
```

You'll get a ruby-head-able interactive container for messing up with some gemsets:

```
docker run -t -i rcmorano/ubuntu-rvm:saucy
```
