## Docker Commands

- docker build -t foo:latest . && docker run -it --rm --name ok foo:latest ls && date && python3 python-hello/hello.py
- docker build -t foo:latest . 
- docker build .
- docker tag dc8ff22f55f4 foo:latest
- docker run -it --rm --name ok foo:latest ls 
- date
- python3 python-hello/hello.py
- docker-compose up foo redis
- docker image prune -a //Remove Ununsed and Dangling Images
- docker image prune //Remove Dangling Images -  unused and having no names
- docker-compose up redis foo //Starts 2 given services - foo, redis