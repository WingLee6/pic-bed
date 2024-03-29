# pic-bed

<!-- @import "[TOC]" {cmd="toc" depthFrom=1 depthTo=6 orderedList=false} -->

<!-- code_chunk_output -->

- [pic-bed](#pic-bed)
  - [仓库简介](#仓库简介)
  - [使用软件获取Markdown图片地址](#使用软件获取markdown图片地址)
  - [直接在GitHub网页复制Markdown图片地址](#直接在github网页复制markdown图片地址)

<!-- /code_chunk_output -->

## 仓库简介
GiHub图床，用于存储在线图片。
1. 仓库地址:
https://github.com/lukelee98/pic-bed.git
2. 文件结构:  
    除了`README.md`文件外，按年份将图片创建目录。   
    >如2022年则创建目录`pic2022`.

## 使用软件获取Markdown图片地址
1. 软件名称:
    **PicGo**
2. 软件下载地址:
    https://github.com/Molunerfinn/PicGo
3. 软件设置:
    1. 找到软件，右键->打开详细窗口->图床设置->GitHub图床；
    2. GitHub设置如下：
        + 设定仓库名： lukelee98/pic-bed
        + 设定分支名：main
        + 设定Token：****************
        + 指定存储路径：pic2023/

4. 上传图片直接拖拽，获取图片地址直接点击  
    也可设置链接的格式（纯图片链接、MD格式、HTML格式等），如：
    ![](https://raw.githubusercontent.com/lukelee98/PicBed/main/Pic2022/chunk.png)

5. 从**PicGo**拷贝来的地址乱码
    + 原因：图片名称带有中文的缘故  
    + 解决：将乱码部分（UTF-8）转成汉字（如，`测试` <--> E6B58B E8AF95)  
        可以使用在线转换器：https://www.qqxiuzi.cn/bianma/zifuji.php

## 直接在GitHub网页复制Markdown图片地址
步骤：
1. 找到需要的图片，如：  
    【地址1】:   
    https://github.com/lukelee98/pic-bed/blob/main/pic2022/getMarkDownOicBedAddressofGitHub.png
    
2. 图片->右键->拷贝图像地址，即可得到，如：  
    【地址2】:  
    https://github.com/lukelee98/pic-bed/blob/main/pic2022/getMarkDownOicBedAddressofGitHub.png?raw=true  
    
    **注意**：和上面【地址1】的区别就是后面增加了`?raw=true`，表示可以直接展示.  

3. 改成Markdown插入图片格式：  
    ```markdown
    ![](【地址2】)
    或
    ![](【地址1】?raw=true)
    ```

    ![](https://github.com/lukelee98/pic-bed/blob/main/pic2022/getMarkDownOicBedAddressofGitHub.png?raw=true)