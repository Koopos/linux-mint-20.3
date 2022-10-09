# 装机必备软件

## 翻墙软件shadowSocks
[下载地址](./Trojan-Qt5-Linux.1.1.6.7z)
配置文件
```
https://jmssub.net/members/getsub.php?service=468711&id=d6c76a12-f124-4676-827a-df82a8b9aaff

ss://YWVzLTI1Ni1nY206OXJNbTdad0t0dlFLdDh2d0A0NS43OC40LjcxOjI3MjAx#JMS-468711@c53s1.jamjams3.net:27201
ss://YWVzLTI1Ni1nY206OXJNbTdad0t0dlFLdDh2d0A0NS43OC4xMC4xODI6MjcyMDE#JMS-468711@c53s2.jamjams3.net:27201
vmess://eyJwcyI6IkpNUy00Njg3MTFAYzUzczMuamFtamFtczMubmV0OjI3MjAxIiwicG9ydCI6IjI3MjAxIiwiaWQiOiJkNmM3NmExMi1mMTI0LTQ2NzYtODI3YS1kZjgyYThiOWFhZmYiLCJhaWQiOjAsIm5ldCI6InRjcCIsInR5cGUiOiJub25lIiwidGxzIjoibm9uZSIsImFkZCI6IjE5OS4xODAuMTE0LjcxIn0
vmess://eyJwcyI6IkpNUy00Njg3MTFAYzUzczQuamFtamFtczMubmV0OjI3MjAxIiwicG9ydCI6IjI3MjAxIiwiaWQiOiJkNmM3NmExMi1mMTI0LTQ2NzYtODI3YS1kZjgyYThiOWFhZmYiLCJhaWQiOjAsIm5ldCI6InRjcCIsInR5cGUiOiJub25lIiwidGxzIjoibm9uZSIsImFkZCI6IjQ1Ljc4LjUzLjExMSJ9
vmess://eyJwcyI6IkpNUy00Njg3MTFAYzUzczUuamFtamFtczMubmV0OjI3MjAxIiwicG9ydCI6IjI3MjAxIiwiaWQiOiJkNmM3NmExMi1mMTI0LTQ2NzYtODI3YS1kZjgyYThiOWFhZmYiLCJhaWQiOjAsIm5ldCI6InRjcCIsInR5cGUiOiJub25lIiwidGxzIjoibm9uZSIsImFkZCI6IjEwNC4yNTUuNjUuMTExIn0
vmess://eyJwcyI6IkpNUy00Njg3MTFAYzUzczgwMS5qYW1qYW1zMy5uZXQ6MjcyMDEiLCJwb3J0IjoiMjcyMDEiLCJpZCI6ImQ2Yzc2YTEyLWYxMjQtNDY3Ni04MjdhLWRmODJhOGI5YWFmZiIsImFpZCI6MCwibmV0IjoidGNwIiwidHlwZSI6Im5vbmUiLCJ0bHMiOiJub25lIiwiYWRkIjoiMjMuODMuMjI3LjE1NiJ9
```

## 搜狗输入法 
[下载](./sogoupinyin_4.0.1.2800_x86_64.deb)

## docker
```bash
 sudo apt-get install docker-io
```

docker.yml
```
version: '3.3'
services:
    mysql:
        ports:
            - '3306:3306'
        volumes:
            - '/mnt/sde/mysql:/var/lib/mysql'
        environment:
            - MYSQL_ROOT_PASSWORD=123456
        container_name: mysql
        image: mysql

    nextcloud:
        restart: always
        ports:
            - '8000:80'
        volumes:
            - '/mnt/sde/nextcloud:/var/www/html'
        container_name: nextcloud
        image: nextcloud

```

### 迅雷 for linux
[下载](./com.xunlei.download_1.0.0.1_amd64.deb)

## anaconda

## nodejs

## vim spf13

```bash
git clone https://github.com/spf13/spf13-vim.git
./bootstrap.sh
```

## vscode
[下载](./code_1.72.0-1664926972_amd64.deb)

## nvidia驱动