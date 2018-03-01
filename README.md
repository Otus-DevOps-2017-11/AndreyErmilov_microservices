# AndreyErmilov_microservices

## Homework 14

### Знакомство с docker
В домашнем задании:
- скачали и запустили `docker run -it ubuntu:16.04 /bin/bash`
- посмотрели какие образы скачаны `docker images`, какие контейнеры запущены `docker ps` и какие существуют `docker run -it ubuntu:16.04 /bin/bash`
- запустили процесс `bash` внутри контейнера `docker exec -it <u_container_id> bash`
- создали образ из запущенного контейнера `docker commit <u_container_id> yourname/ubuntu-tmp-file`
- удалили образы `docker rmi` и контейнеры `docker rm`
