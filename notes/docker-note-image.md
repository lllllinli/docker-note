#Docker - image 常用指令




基本用法

##Docker Hub 檔案規則：

- 三個參數

```
[user-name]/[repo-name]:[tag-name]
```

1.參數一 ，user name (office 通常沒有)
    
    - Docker hub 上註冊的名字
    
2.參數二 ，repo name (必填)

    - Docker hub  repo 的名稱

3.參數三 ，tag name (非必填)

    - 要分辨同一個倉庫中的不同映像檔，就要用tag name來區分。
      
      - 如果該倉庫中只有一個映像檔，則tag name可以省略。
      
      - 如果該倉庫中有多個映像檔，在沒有指定tag name時，以最新的一個為主。
      
      - 同一個映像檔可以有多個tag name，可看做是別名。可以從相同的映像檔ID看出來。



## [ 列出 ] 目前的 image

```
$ docker images
```

參數：

    (1) -a :        
        列出完整 image
        
    (2) -q :
        只列出 id
        

## [ 載入 ] pull image

1.一般 image 

```
$ docker pull [repo-name]
```

參數：

    (1) -a :        
        下載某 repo 全部的 image
        

## [ 匯出/存入 ] image



