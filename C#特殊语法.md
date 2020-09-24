---
title:C#特殊语法
---

* var的使用

用来代替某些具体的类型，由编译器自动判断变量类型，编译器可以根据变量的初始化值"推断"变量的类型。

代替具体类型，实现快速编程的隐式类型用法，常见在foreach便历中，实质是VS编译器给我们提供的一个语法糖

和new 一起使用，来实现一个匿名类型，用来代替需要预先创建的实体类，灵活高效

~~~C#
var annoyCla1 = new
    {
        ID = 10010,
        Name = "EdisonChou",
        Age = 25
    };
~~~

* =>运算符

用于表示lambda表达式。

写法：所有Lambda表达式都使用Lambda运算符=>，该运算符读作"goes to"。Lambda运算符的左边是输入参数(如果有)，右边是表达式或语句块。
Lambda表达式x => x * x 读作"x goes to x times x"。

Expression lambda that has an expression as its body:

	(input-parameters) => expression

Statement lambda that has a statement block as its body:

	(input-parameters) => { <sequence-of-statements> }

使用 lambda 声明运算符=> 从其主体中分离 lambda 参数列表。 若要创建Lambda表达式，需要在 Lambda 运算符左侧指定输入参数（如果有），然后在另一侧输入表达式或语句块。

异步 lambda 的使用要注意。

* BindingSource

https://docs.microsoft.com/zh-cn/dotnet/api/system.windows.forms.bindingsource?view=netcore-3.1

BindingSource组件是数据源和控件间的一座桥,同时提供了大量的API和Event供我们使用。使用这些API我们可以将Code与各种具体类型数据源进行解耦；使用这些Event我们可以洞察数据的变化。

* ObservableCollection 





