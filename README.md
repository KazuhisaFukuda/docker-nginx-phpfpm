# Nginx + PHP-FPM
Dockerを使用したPHPの開発環境(Nginx + PHP-FPM)を構築

## ツール
* Docker for Windows (or Max)
* Docker ToolBox

## 使用したイメージ
* nginx:1.14.0-alpine [(OFFICIAL)](https://hub.docker.com/_/nginx/)
* php:7.1.17-fpm [(OFFICIAL)](https://hub.docker.com/_/php/)
* mysql:latest [(OFFICIAL)](https://hub.docker.com/_/mysql/)
* busybox:latest [(OFFICIAL)](https://hub.docker.com/_/busybox/)

## 環境情報
* PHP    7.1.17
* Nginx  1.14.0
* MySQL  8.0.11

## 使用方法
```
1. git clone https://github.com/KazuhisaFukuda/docker-nginx-phpfpm.git
2. cd docker-nginx-phpfpm
3. docker-compose up -d
```

## PHPINFO
| ツール | アクセス |
|:-----------|:-----------|
| docker for windows (or mac) | http://localhost |
| docker toolbox | http://192.168.99.100 |
