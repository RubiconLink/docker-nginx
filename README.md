# docker-nginx

Docker で Nginx を動かす。

# Usage

```
$ git clone https://github.com/RubiconLink/docker-nginx.git
$ cd docker-nginx
$ sudo docker build -t quest-dev-docker .
$ sudo docker run --rm -d -p 80:80 quest-dev-docker
$ docker ps
```
