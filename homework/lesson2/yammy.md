## 为什么编程语言需要多样化的数据格式？

~~以下是我的个人理解：~~

~~一般来说，编程的目的就是：**处理数据，得到结果**，我们想要得到一个期望的结果，其中必然需要处理数据，甚至可能需要处理不同的数据，处理海量的数据。~~

~~拿小明这位同学举个栗子，从小明身上，根据属性的不同，我们可以找到不同的数据，比如姓名、身高、年龄、五官、家人情况、家庭住址、学校情况、学校地址。。。把这些所有的属性归纳在一起，就等价于小明这位小盆友。~~

~~如果小明有这些属性，那么换个人是否也有同样的属性呢？~~

~~哦，原来小花、小塔都有一些相同的属性：姓名、身高、年龄、家庭情况、学校情况。。~~

~~那么我们是否可以考虑把这些属性抽象出来，作为所有人的共同属性呢？~~

~~回到编程语言，小明、小花、小塔就是我们编程中所说的对象，所有的对象都有共同的属性，这些属性抽象出来可能就是：字符串、数字、布尔值、数组和字典。~~

~~回到问题本身，编程语言之所以需要多样化的数据格式，就是要尽可能准确的存储对象的属性值，确保这些属性值拼接在一起可以等价于对象本身。~~

**20170817 更新：**

1. 根据所要描述的对象的不同，使用合适的数据类型

我们想要描述的对象，有时候千差万别，为了尽可能准确的描述它们，所以我们需要多样化的数据格式。

编程的本质就是：**处理数据，得到结果**，以 JS 举例，其常用的数据类型有：string、number、boolean、null、undefined、function、array和 object等，不同的数据类型处理的难度不同，为了尽可能的让数据处理的更快，我们需要选择最合适的数据类型。

比如，如果我们只需要处理一个人的年龄数据，我们可以定义一个对象：

```
var xiaohua_info = {
	age: 20;
}
```

得到小花的年龄的方式是调用对象的 name 属性：`console.log(xiaohua_info.name);`

当然，我们也可以直接定义一个 number：

`var xiaohua_age = 20`

那么，得到小花的年龄的方式就相对简单：`console.log(xiaohua_age);`

很明显，在这里后者是更加适合的方式。


2. 不同的数据类型，决定了代码被机器执行的效率

不同的数据类型，其占用的计算机内存是不一样的，为了尽可能的利用计算机的存储资源以及提高计算机执行代码的效率（效率主要反应在存储效率、计算效率和传递效率上），我们需要选择合适的数据类型。

另外，不同的数据类型,会告诉编译器或解释器，我们该如何使用这个数据。

## my page

[my-page](https://yammmy.github.io/my-page/)
