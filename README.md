# Docker-Only-Office-Chinese-font

## 介绍

本项目是为Docker 构建的 Only Office ＋ nextcloud ，onlyoffice中添加中文字体。

## 使用方法

```
git clone https://github.com/neroxps/Docker-Only-Office-Chinese-font.git
cd Docker-Only-Office-Chinese-font
docker container cp ./ onlyoffice-document-server:/usr/share/fonts/
docker exec -it onlyoffice-document-server bash
sudo bash documentserver-generate-allfonts.sh

```
然后清除浏览器缓存，就可以使用了，在onlyoffice 中宋体为simsun

