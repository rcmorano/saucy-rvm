# How to use

You can just pull the image from the official 'docker' index since it's a trusted build linked with github 'Dockerfile' in this repo:
```
docker pull rcmorano/saucy-rvm
```

Or you can build the image yourself:
```
git clone https://github.com/rcmorano/saucy-rvm.git
docker build -t rcmorano/saucy-rvm:ruby-2.1.0 saucy-rvm/
```
