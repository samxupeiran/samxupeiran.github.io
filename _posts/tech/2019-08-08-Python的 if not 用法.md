---
layout: post
title: Python if not 用法
category: 技术
tags: sam
---

### python中的not具体表示是什么：
### 布尔型True和False，not True为False，not False为True，以下是几个常用的not的用法：
---
(1) not与逻辑判断句if连用，代表not后面的表达式为False的时候，执行冒号后面的语句。比如：
```
a = False
if not a:   (这里因为a是False，所以not a就是True)
    print "hello"
```
---
(2) 判断元素是否在列表或者字典中，if a not b，a是元素，b是列表或字典，这句话的意思是如果a不在列表b中，那么就执行冒号后面的语句，比如：
```
a = 5
b = [1, 2, 3]
if a not in b:
    print "hello"
```
这里也能够输出结果hello