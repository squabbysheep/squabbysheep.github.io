---
title: Pip
date: 2020-03-17 16:00:09
tags:
- Pip
categories:
- Pip
keywords:
---

#### 设置pip源

```
cd  # 回到家目录
mkdir .pip
vim .pip/pip.conf
写入如下内容
[global]
timeout = 6000
index-url = http://pypi.douban.com/simple
trusted-host = pypi.douban.com
```

