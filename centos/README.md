ocker CentOS Container
=======================

```
$ docker images
REPOSITORY          TAG                 IMAGE ID            CREATED             SIZE
centos              latest              d123f4e55e12        10 days ago         197MB
```

* docker pull centos
* docker images
* docker run d123f4e55e12 echo "Hello World"
* docker run -i -t d123f4e55e12


### Run docker in background

* docker run -d d123f4e55e12 sleep 1000
* docker run --rm d123f4e55e12 sleep 10
* docker ps
* docker ps -a


### Docker Detach Mode 

* docker run -d d123f4e55e12 sleep 100
* docker inspect 5bbd16593f8f9173ef02e05dbcc0dd709be656cf2f5e54aacbb4854b072b1042
