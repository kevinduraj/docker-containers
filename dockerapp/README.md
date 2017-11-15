dockerapp
=========

### Build a Container
* docker build -t dockerapp:v0.3 .

### Start Container
* docker run -d -p 5000:5000 dockerapp:v0.3

### Redis
* docker run -d --name redis redis:3.2.0 
* docker stop 917c6dbeb224

### Execute Bash on container
* docker exec -it 0e1f009015d1 bash
 
### Git
* git stash && git checkout v0.2

### Remove Docker Images
* https://www.digitalocean.com/community/tutorials/how-to-remove-docker-images-containers-and-volumes

### Bash Shell
* docker exec -it 917c6dbeb224 bash


### Run application setp by step

```
1. docker run -d --name redis redis:3.2.0 
2. docker ps
3. docker build -t dockerapp:v0.3 .
4. docker run -d -p 5000:5000 --link redis dockerapp:v0.3
5. http://localhost:5000
6. docker stop 2e629f0b730a
```

### Docker Compose
* docker-compose build

* docker-compose up
* docker-compose ps
* docker-compose logs -f
* docker-compose logs dockerapp

* docker-compose stop
* docker-compose rm
