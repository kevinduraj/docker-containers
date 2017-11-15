Build Docker Image
==================

### Download Debian based image

* docker run -it debian:jessie

* apt-get update && apt-get install -y git


### Commit modified image into repository

* docker commit 475c1289ae36 kevin774/debian:1.0

```
$ docker images
'REPOSITORY          TAG                 IMAGE ID            CREATED              SIZE
kevin774/debian     1.0                 8f1ef9a0c601        About a minute ago   219MB
friendlyhello       latest              36d9ab34b518        2 hours ago          148MB
tomcat              latest              11df4b40749f        4 hours ago          558MB
python              2.7-slim            b0259cf63993        10 days ago          138MB
debian              jessie              25fc9eb3417f        10 days ago          123MB
hello-world         latest              725dcfab7d63        10 days ago          1.84kB
```

* docker run -it kevin774/debian:1.0


