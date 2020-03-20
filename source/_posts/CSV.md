---
title: CSV
date: 2020-03-17 01:16:00
tags:
- CSV
categories:
- CSV
keywords:
- CSV
---

#### CSV

```python
with open('test.csv', 'a', encoding='utf-8-sig') as f:
    f.write(','.join(test_list) + '\n')
# 使用utf-8-sig，避免格式错误
# csv是使用","来实现分隔吗,要注意输入值含有逗号会出现结果异常
```

