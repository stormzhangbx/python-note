# list、tuple、dict、set

## list 列表 []

```py
test = ['a', 'b', 'c', 'd']
first = test[0]
```

## tuple 元组 ()

元组中只包含一个元素时，需要在元素后面添加逗号，否则括号会被当作运算符使用：

```py
tupl = ('Jack',)
```

## dict 字典 {}

```py
student = {'name': 'Jack', 'age': 20}
name = student['name']
```

注意这里要区别对象的实例访问属性的方式

```py
class Student(object):
    name = ''
    age = 0

    def __init__(self, name, age):
        self.name = name
        self.age = age


# student = Student('Jack', 20)
student = Student(name='Jack', age=20)
name = student.name
```

## set 集合 {}