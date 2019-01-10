# JDKVersionTree
JDK各版本技术研究

<pre>
JDK5:

      1) 自动装箱与拆箱
      2）枚举
      3）静态导入
      5）可变参数
      6）内省，主要用于操作JavaBean中的属性，通过getXxx/setXxx，一般的做法是通过类
         Introspector来获取某个对象的BeanInfo信息，然后通过BeanInfo来获取属性的
         的描述器，通过这个属性描述器就可以获取某个属性对应的getter/setter方法，然后我们
         就可以通过反射机制来调用这些方法。
      7）泛型
      8）For-Each循环
      9）注解
     
JDK7:

      1) 对于Java集合中Collections的增强支持，可直接采用[],{}形式直接存入对象，
      2）在Switch中可以使用String
      3) 支持二进制数据
      5）简化可变参数调用
      6）Map集合支持并发请求


JDK8:

      1) Lamda表达式
      2）使用::关键字来传递方法或者构造函数引用
      3）多重注解
      5）增加了很多Map相关的API


JDK9:
      1) 集合工厂方法
      2）改进的Stream API
      3) HTTP/2
</pre>
