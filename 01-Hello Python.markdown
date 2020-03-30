> Python的语法采用[PEP8](https://www.jianshu.com/p/26dde1315c74)的编码规范，建议缩进4个空格。
> 如果是顶级代码，那么必须顶格书写，哪怕只有一个空格也会有语法错误。

* 下面示例，满足 if 条件要输出两行内容，这两行内容必须都缩进4个空格（必须具有相同的缩进级别）

```python
print("Hello Python")  # Hello Python


if 8 > 0:
    print("OK")  # ok
    print("YES")  # YES
 
    
x = 3
y = 4  # 不推荐将两个赋值语句写在一行
print(x + y) # 7
```