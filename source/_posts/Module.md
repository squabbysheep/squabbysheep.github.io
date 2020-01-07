---
title: Module
date: 2020-01-07 14:35:32
tags:
- module
categories:
- Python
---

介绍模块相关一些小知识

```python
#!/usr/bin/env python3
# -*- coding: utf-8 -*-

' a test module '

__author__ = 'Michael Liao'

import sys

def test():
    args = sys.argv
    if len(args)==1:
        print('Hello, world!')
    elif len(args)==2:
        print('Hello, %s!' % args[1])
    else:
        print('Too many arguments!')

if __name__=='__main__':
    test()
```



```python
#!/usr/bin/env python3
可以让文件直接在Unix/Linux/Mac上运行
```

```
# -*- coding: utf-8 -*-
统一使用标准utf-8编码
```

