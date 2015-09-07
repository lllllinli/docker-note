#Docker - image 常用指令

## [ 載入 ] pull image

1.一般 image 

```
$ docker pull [option1]/[option2]:[option3]
# option1 - user name
# option2 - repo name
# option3 - tag name
# ex : docker pull ubuntu:09-07
```

## [ 列出 ] 目前的 image

```
$ docker images
```

## [ 修改 ] image

1.執行載入的 image

```
$ docker run -t -i [image-name] /bin/bash
# 
```

