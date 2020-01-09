---
title: centos7-yum
date: 2020-01-09 12:04:59
tags:
- linux
- yum
keywords:
- yum
categories:
- linux
---

#### 安装源和更新

```shell
# 这操作很重要，可以避免很多版本性bug
yum install -y epel-release
yum update -y
```

#### 安装Python

```
yum install python36
```

#### 安装Redis

```
yum install redis
# 配置文件默认在/etc/redis.conf 
# redis-server /etc/redis.conf  # 运行服务
# redis-cli -a password  # 登录
```

```
编译安装redis链接：https://blog.csdn.net/qq_39185919/article/details/100564713
```

