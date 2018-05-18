# Nginx + PHP-FPM
Dockerを使用したPHPの開発環境(Nginx + PHP-FPM)を構築

## ツール
* Docker for Windows (or Max)
* Docker ToolBox

## イメージ
* nginx:1.14.0-alpine [(OFFICIAL)](https://hub.docker.com/_/nginx/)
* php:7.1.17-fpm [(OFFICIAL)](https://hub.docker.com/_/php/)
* mysql:latest [(OFFICIAL)](https://hub.docker.com/_/mysql/)
* busybox:latest [(OFFICIAL)](https://hub.docker.com/_/busybox/)

## 使用方法
```
1. git clone https://github.com/Kazuo123/docker-nginx-phpfpm.git
2. cd docker-nginx-phpfpm
3. docker-compose up -d
```
