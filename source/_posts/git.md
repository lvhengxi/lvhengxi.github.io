---
title: git简单使用 
date: 2020-10-23 22:48:25
tags:
---

git
=========

# github和git

第三次学习使用git+github了,这次不在要求什么都会了，只要求最简单的实现就行，

# 开始

## 第一步

需要让git知道你是谁  

    git config --global user.name "xxx"
    git config --global user.email "xxx"

## 第二步
去github创建一个仓库，毕竟自己用不着在本地版本跳来跳去，ctrl+z不香吗？

然后使用git clone 取下来一般的链接形式都是

    https://github.com/user.name/yours_repository_name

## 第三步
将文件上传到github。

要上传，首先需将文件给git管理

    git add file_name
然后需要提交到本地的git版本库，将版本的快照保存起来

    git commit -m "这里写上注释，比如hello world"

最后push到repository

    git push

## 其他

最重要的命令之一，随时查看你的git状态

    git status  

删除仓库里的文件 

    git rm -r --cache  
这时你的文件会不被git管理，这时只需将你的git再push一次即可

## 最后
反正学多了也记不住，不就这样先用起来，不会的再慢慢学
