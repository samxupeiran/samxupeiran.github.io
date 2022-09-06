---
layout: post
title: Python if not 用法
category: Tech
tags: Python
---
#### python 中的 not 具体表示是什么：
#### 布尔型 True 和 False，not True 为 False，not False 为 True，以下是几个常用的 not 的用法：
---
(1) not 与逻辑判断句 if 连用，代表 not 后面的表达式为 False 的时候，执行冒号后面的语句。比如：
```
a = False
if not a:   (这里因为 a 是 False，所以 not a 就是 True)
    print "hello"
```
---
(2) 判断元素是否在列表或者字典中，if a not b，a 是元素，b 是列表或字典，这句话的意思是如果 a 不在列表b中，那么就执行冒号后面的语句，比如：
```
a = 5
b = [1, 2, 3]
if a not in b:
    print "hello"
```
这里也能够输出结果 hello