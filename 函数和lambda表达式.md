# 1.给函数编写文档


```python
def MyFunction(name):
    "函数文档"
    print("传递来的参数内容{0}是".format(name))
MyFunction("helo world")
help(MyFunction)
```

    传递来的参数内容helo world是
    Help on function MyFunction in module __main__:
    
    MyFunction(name)
        函数文档
    
    

# 2.怎么给函数参数和返回值注解

## 常规注解即可

# 3.闭包中，怎么对数字、字符串、元组等不可变元素更新。

## 声明nonlocal 然后进行赋值
