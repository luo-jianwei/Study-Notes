### 导入中文编码
- `# -*- coding: UTF-8 -*-`
- `#coding=utf-8`

### 去掉前后空格和输出字符长度
- `strip()`
- `len()`  

```
In [17]: a = '    '

In [18]: len(a)
Out[18]: 4

In [19]: b = a.strip()

In [20]: len(b)
Out[20]: 0
```

### range函数:返回一系列连续增加的整数
- `range(起始值,结束值,步进值)`

```
In [31]: range(1,10)
Out[31]: [1, 2, 3, 4, 5, 6, 7, 8, 9]

In [32]: range(1,10,3)
Out[32]: [1, 4, 7]
```
