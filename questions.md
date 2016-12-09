<pre>
<h4>1.volatile关键字的说法错误的是（ ）</h4>
A.能保证线程安全

B.volatile关键字用在多线程同步中，可保证读取的可见性

C.JVM保证从主内存加载到线程工作内存的值是最新的

D.volatile能禁止进行指令重排序

正确答案: A
</pre>
<pre>
<h4>2.下列说法错误的有（ ）(多选)</h4>
A.Java面向对象语言容许单独的过程与函数存在

B.Java面向对象语言容许单独的方法存在

C.Java语言中的方法属于类中的成员（member）

D.Java语言中的方法必定隶属于某一类（对象），调用方法与过程或函数相同

正确答案: A B C
</pre>
<pre>
<H4>3.下列选项中是正确的方法声明的是？（）(多选)</H4>
A.protected abstract void f1();

B.public final void f1() {}

C.static final void fq(){}

D.private void f1() {}

正确答案: A B C D
</pre>
<pre>
	<h4>4.从运行层面上来看，从四个选项选出不同的一个（）</h4>
A.JAVA

B.Python

C.objectC

D.C#

正确答案: B
</pre>
<pre>
<h4>5.下面程序的输出是什么？	</h4>
package algorithms.com.guan.javajicu;
public class TestDemo
{
    public static String output = ””;
    public static void foo(inti)
    {
        try
        {
            if (i == 1)
            {
                throw new Exception();
            }
        }
        catch (Exception e)
        {
            output += “2”;
            return ;
        } finally
        {
            output += “3”;
        }
        output += “4”;
    }
    public static void main(String[] args)
    {
        foo(0);
        foo(1);
        System.out.println(output);
    }
}

A.342

B.3423

C.34234

D.323

正确答案: B  
</pre>
<pre>
<h4>6.在try的括号里面有return一个值，那在哪里执行finally里的代码？</h4>
A.不执行finally代码

B.return前执行

C.return后执行

正确答案: B  
</pre>
<pre>
<h4>7.选项中哪一行代码可以添加 题目中而不产生编译错误？</h4>
public abstract class MyClass {
     public int constInt = 5;
     //add code here
     public void method() {
     }
}

A.public abstract void method(int a);

B.constInt = constInt + 5;

C.public int method();

D.public abstract void anotherMethod() {}

正确答案: A 
</pre>
<pre>
<h4>8.以下哪项不属于java类加载过程？</h4>
A.生成java.lang.Class对象

B.int类型对象成员变量赋予默认值

C.执行static块代码

D.类方法解析

正确答案: B
</pre>
<pre>
<h4>9.下列 java 程序输出结果为______。 </h4>
int i=0;
Integer j = new Integer(0);
System.out.println(i==j);
System.out.println(j.equals(i));

A.true,false

B.true,true

C.false,true

D.false,false

E.对于不同的环境结果不同

F.程序无法执行

正确答案: B 
</pre>
<pre>
<h4>10.abstract class和interface有什么区别。(多选)</h4>
A.抽象类可以有构造方法，接口中不能有构造方法

B.抽象类中可以有普通成员变量，接口中没有普通成员变量

C.抽象类中不可以包含静态方法，接口中可以包含静态方法

D.一个类可以实现多个接口，但只能继承一个抽象类。

正确答案: A B D
</pre>
<pre>
<h4>11.下列Java代码中的变量a、b、c分别在内存的____存储区存放。</h4> 
class A {
    private String a = “aa”;
    public boolean methodB() {
        String b = “bb”;
        final String c = “cc”;
    }
}

A.堆区、堆区、堆区

B.堆区、栈区、堆区

C.堆区、栈区、栈区

D.堆区、堆区、栈区

E.静态区、栈区、堆区

F.静态区、栈区、栈区

正确答案: C 
</pre>
<pre>
<h4>12.有关下述Java代码描述正确的选项是____。 </h4>
public class TestClass {
   private static void testMethod(){
        System.out.println("testMethod");
   }
   public static void main(String[] args) {
        ((TestClass)null).testMethod();
   }
}

A.编译不通过

B.编译通过，运行异常，报NullPointerException

C.编译通过，运行异常，报IllegalArgumentException

D.编译通过，运行异常，报NoSuchMethodException

E.编译通过，运行异常，报Exception

F.运行正常，输出testMethod

正确答案: F  
</pre>
<PRE>
<H4>13.下列不属于算法结构的是（）</H4>
A.输入数据

B.处理数据

C.存储数据

D.输出结果

正确答案: C
算法包括0个或多个输入，1个或多个输出，中间有穷个处理过程。
存储结构不属于算法结构
</PRE>
<PRE>
<H4>14.下列说法正确的有（ ）(多选)</H4>
A.环境变量可在编译source code时指定

B.在编译程序时，所能指定的环境变量不包括class path

C.javac一次可同时编译数个Java源文件

D.javac.exe能指定编译结果要置于哪个目录（directory）

正确答案: A C D 
a选项-d即可设置系统属性
c选项一次编译多个java文件用javac *.java. 即可编译当前目录下的所有java文件
d选项－s指定存放生成的源文件的位置 
</PRE>
<pre>
<h4>15.以下哪个不是Collection的子接口？</h4>
A.List

B.Set

C.SortedSet

D.Map

正确答案: D
</pre>
<PRE>
<H4>16.在J2EE中，使用Servlet过滤器，需要在web.xml中配置（）元素(多选)</H4>
A.&lt;filter>

B.&lt;filter-mapping>

C.&lt;servlet-filter>

D.&lt;filter-config>

正确答案: A B 
</PRE>
<pre>
<h4>17.JAVA反射机制主要提供了以下哪些功能？(多选)</h4>
A.在运行时判断一个对象所属的类

B.在运行时构造一个类的对象

C.在运行时判断一个类所具有的成员变量和方法

D.在运行时调用一个对象的方法

正确答案: A B C D 
</pre>
<pre>
<h4>18.下面有关java实例变量,局部变量,类变量和final变量的说法，错误的是？</h4>
A.实例变量指的是类中定义的变量，即成员变量，如果没有初始化，会有默认值。

B.部变量指的是在方法中定义的变量，如果没有初始化，会有默认值

C.量指的是用static修饰的属性

D.nal变量指的是用final 修饰的变量

正确答案: B
定义在类中的变量是类的成员变量，可以不进行初始化，Java会自动进行初始化，如果是引用类型默认初始化为null,如果是基本类型例如int则会默认初始化为0
局部变量是定义在方法中的变量，必须要进行初始化，否则不同通过编译
被static关键字修饰的变量是静态的，静态变量随着类的加载而加载，所以也被称为类变量
被final修饰发变量是常量 
</pre>
<PRE>
<H4>19.个hibernate延迟加载，说法错误的是？</H4>
A.bernate2延迟加载实现：a)实体对象 b)集合（Collection）

B.bernate3 提供了属性的延迟加载功能

C.t支持延迟加载，load不支持延迟加

D.bernate使用Java反射机制，而不是字节码增强程序来实现透明性

正确答案: C 
</PRE>
<pre>
<h4>20.计中，类的成员变量要求仅仅能够被同一package下的类访问，请问应该使用下列哪个修饰词（）</h4>
A.protected

B.public

C.private

D.不需要任何修饰词

正确答案: D  
</pre>
<pre>
<h4>一般情况下，以下哪个选项不是关系数据模型与对象模型之间匹配关系？</h4>
A.表对应类

B.记录对应对象

C.表的字段对应类的属性

D.表之间的参考关系对应类之间的依赖关系

正确答案: D 
</pre>
<PRE>
<H4>以下代码输出的是： </H4>
public class SendValue{
    public String str="6";
    public static void main(String[] args) {
        SendValue sv=new SendValue();
        sv.change(sv.str);
        System.out.println(sv.str);
    }
    public void change(String str) {
        str="10";
    }
}

A.6

B.10

C.都不对

D.16

正确答案: A 
 Java中String类型变量是immutable（不可变的）。
尽管 change()方法中的str与sv.str都是新的对象实例成员变量值"6"的引用， 由于String类型的 不可变 性，change()方法中的str="10"语句实际上是将传入的str副本引用指向了一个值为“10”的新的内存地址，但 原数据引用 sv.str的引用值（也就是“6”的内存地址） 并没有发生改变，因此sv.str指向的值仍旧为6. 
</PRE>
