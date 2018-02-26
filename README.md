# composer-cn
启用了Packagist / Composer中国全量镜像的composer容器镜像

[![DockerHub Badge](http://dockeri.co/image/zhangsean/hello-web)](https://hub.docker.com/r/zhangsean/hello-web/)

### 用法
进入含有composer.json的项目文件夹，直接运行容器执行install即可：
```
docker run -it --rm -v $PWD:/app zhangsean/composer-cn install
```

也可以直接执行composer的命令，比如：
```
docker run -it --rm -v $PWD:/app zhangsean/composer-cn run-frontend
```
