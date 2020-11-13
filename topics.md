# Docker

- Install docker
- Create application
- Version control application
- Build Docker image
``` shell
    docker build --tag n1 .
```
- Run Docker container
``` shell
    docker run -p 10000:80 -d --name n1_1 n1
    docker ps -a
    docker stop n1_1
    docker start n1_1
``` 
- Publish Docker image
``` shell
    docker tag 6110520134/cn30:tagname
    docker push 6110520134/cn330:tagname
``` 