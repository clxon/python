# 我的神奇Python教程(7)

上一篇我们讨论了神奇的变量，今天，咱好♂好说说变量的数据类型

首先，Python的数据类型并不需要手动指定，甚至变量也不需要声明。

首先，来看看`int`类型:

```python
>>> i = 500
>>> type(i) # type 函数可以拿到变量的类型
<class 'int'> # 这个class int就是i的类型
```

`type`函数用于取得变量的类型，这里我们发现，`i`是`int`类型！

哦天啊，那它可以做什么呢？

对，我们可以计算他！

什么`i + 1`,`i * 9`,`5 * 5 * 5`都可以被计算出结果！

*******

下一个，`float`类型。

和`int`一样，它也是一种数值，不过是小数:

```python
>>> f = 2.33333
>>> type(f)
<class 'float'>
```

********

第三个，`str`类型。`str`是`string`的缩写，他是字符串:

```python
>>> s = 'Hello,World!' # s是一个字符串
>>> type(s)
<class 'str'>
```

`str`类型可以加:` 'Hello' + 'World' `，这个表达式就等于`'HelloWorld'`。

今天，我们神奇的学习了个种数据类型(就三种)，我们之后还会学到更多的数据类型。

没听懂也没事，我之后还会讲。

[上一篇](https://clxon.github.io/python/6) [下一篇](https://clxon.github.io/python/8)