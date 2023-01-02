<!--  ![Java 中的类](https://www.runoob.com/wp-content/uploads/2013/12/20210105-java-object-1.png)
-->

<img src="https://www.runoob.com/wp-content/uploads/2013/12/20210105-java-object-1.png" width="60%">


<img src="https://www.runoob.com/wp-content/uploads/2013/12/20210105-java-object-1.png" width = 40% height = 40% />

```java
public class Dog {
    String breed;
    int size;
    String colour;
    int age;
 
    void eat() {
    }
 
    void run() {
    }
 
    void sleep(){
    }
 
    void name(){
    }
}
```

一个类可以包含以下类型变量：

**局部变量**：在方法、构造方法或者语句块中定义的变量被称为局部变量。变量声明和初始化都是在方法中，方法结束后，变量就会自动销毁。

**成员变量**：成员变量是定义在类中，方法体之外的变量。这种变量在创建对象的时候实例化。成员变量可以被类中方法、构造方法和特定类的语句块访问。

**类变量**：类变量也声明在类中，方法体之外，但必须声明为 static 类型。

一个类可以拥有多个方法，在上面的例子中：
```java
eat()
run()
sleep() 
name() 
```
都是 Dog 类的方法。

构造方法
每个类都有构造方法。如果没有显式地为类定义构造方法，Java 编译器将会为该类提供一个默认构造方法。

在创建一个对象的时候，至少要调用一个构造方法。构造方法的名称必须与类同名，一个类可以有多个构造方法。

下面是一个构造方法示例：
