---
author: Shu Pengfei
title:  vagrant up yo
---
== data-rotate="20" data-scale="10" data-x="1000"

#  <center> Vagrant  <center>

## <center>new way in cooperation</center>

---
== data-rotate="20" data-scale="10" data-x="200"

##我的电脑上是可以的啊?!
### 真想把你的电脑要过来啊!
---
=== data-x="1000"

# 妈妈说:
## 为人要大方一点
## 给你就给你!

---
=== data-x="1000"

# 怎么给呢?

---
=== data-x="1000"
# vagrant 来帮你
## 基于虚拟机技术( virtual box)的一套命令行工具
## 方便虚拟机 定制/发布

# 统一协作
---
=== data-x="1000"

1. 安装 Virtual Box (VirtualBox-4.2.16-86992-Win.exe)
2. 安装 vagrant (<http://www.vagrantup.com/>)
3. 下载需要的boxes (<http://www.vagrantbox.es/>)
4. 折腾 折腾 折腾
5. 分享

---
=== data-x="1000"

## 基本节奏

```bash
$ vagrant box add boxname  boxURL/Path
$ //example
$ vagrant box add bsd  d:/FreeBSD-8.4-i386.box
$ cd to/your/workspace/
$ vagrant init bsd
$ vagrant up
$ vagrant ssh
```
---
=== data-x="1000"

## 虚拟世界
```bash
% do sth awesomt
% exit
```
## 现实世界
```bash
$ vagrant halt     // 关闭虚拟机
$ vagrant package  // 打包虚拟机
$ ls package.box   // 新的box 分享你的成果
```

---
== data-rotate="20" data-scale="10" data-x="1000"

# Why
### 0. 很久没有出来吹牛了
### 1. 协作
### 2. dmxsee 安装我不喜欢
### 3. linsee 忙碌的IO, 如果能在自己搞定这个如何/ Ccheckout product
### 4. CI server  本地过了/CI server不过.
### 5. CI 服务器部署/异构服务器/Sandbox
### 6. provider for mcRNC/openMGW

----


# 买一送一
## <http://devdocs.io/>







