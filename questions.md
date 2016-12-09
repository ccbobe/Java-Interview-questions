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
<H4>19.下面几个关于hibernate延迟加载，说法错误的是？</H4>
A.bernate2延迟加载实现：a)实体对象 b)集合（Collection）

B.bernate3 提供了属性的延迟加载功能

C.t支持延迟加载，load不支持延迟加

D.bernate使用Java反射机制，而不是字节码增强程序来实现透明性

正确答案: C 
</PRE>
<pre>
<h4>20.JAVA设计中，类的成员变量要求仅仅能够被同一package下的类访问，请问应该使用下列哪个修饰词（）</h4>
A.protected

B.public

C.private

D.不需要任何修饰词

正确答案: D  
</pre>
<pre>
<h4>21.一般情况下，以下哪个选项不是关系数据模型与对象模型之间匹配关系？</h4>
A.表对应类

B.记录对应对象

C.表的字段对应类的属性

D.表之间的参考关系对应类之间的依赖关系

正确答案: D 
</pre>
<PRE>
<H4>22.以下代码输出的是： </H4>
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
尽管 change()方法中的str与sv.str都是新的对象实例成员变量值"6"的引用， 由于String类型的 不可变 性,
change()方法中的str="10"语句实际上是将传入的str副本引用指向了一个值为“10”的新的内存地址,
但 原数据引用 sv.str的引用值（也就是“6”的内存地址） 并没有发生改变，因此sv.str指向的值仍旧为6. 
</PRE>
<pre>
<h4>23.关于sleep()和wait()，以下描述错误的一项是（ ）</h4>
A.sleep是线程类（Thread）的方法，wait是Object类的方法；

B.sleep不释放对象锁，wait放弃对象锁

C.sleep暂停线程、但监控状态仍然保持，结束后会自动恢复

D.wait后进入等待锁定池，只有针对此对象发出notify方法后获得对象锁进入运行状态

正确答案: D
D错是因为进入的是就绪状态而不是运行状态 
</pre>
<PRE>
<H4>24.Java中用正则表达式截取字符串中第一个出现的英文左括号之前的字符串。
比如：北京市（海淀区）（朝阳区）（西城区），截取结果为：北京市。正则表达式为（）</H4>
A.".*?(?=\\()"

B.".*?(?=\()"

C.".*(?=\\()"

D.".*(?=\()"

正确答案: A 
前面的.*?是非贪婪匹配的意思， 表示找到最小的就可以了
(?=Expression) 顺序环视，(?=\\()就是匹配正括号

String text = "北京市(海淀区)(朝阳区)(西城区)";
Pattern pattern = Pattern.compile(".*?(?=\\()" );
Matcher matcher = pattern.matcher(text);
if (matcher.find()) {
System.out.println(matcher.group(0));
} 
</PRE>
<pre>
<h4>25.在java中重写方法应遵循规则的包括（）(多选)</h4>
A.访问修饰符的限制一定要大于被重写方法的访问修饰符

B.可以有不同的访问修饰符

C.参数列表必须完全与被重写的方法相同

D.必须具有不同的参数列表

正确答案: B C
方法的重写（override）两同两小一大原则：
方法名相同，参数类型相同
子类返回类型小于等于父类方法返回类型，
子类抛出异常小于等于父类方法抛出异常，
子类访问权限大于等于父类方法访问权限。
</pre>
<pre>
<h4>26.下面有关java内存模型的描述，说法错误的是？</h4>
A.JMM通过控制主内存与每个线程的本地内存之间的交互，来为java程序员提供内存可见性保证

B.“synchronized” — 保证在块开始时都同步主内存的值到工作内存，而块结束时将变量同步回主内存

C.“volatile” — 保证修饰后在对变量读写前都会与主内存更新。

D.如果在一个线程构造了一个不可变对象之后（对象仅包含final字段），就可以保证了这个对象被其他线程正确的查看

正确答案: D 
final只是指向不变，但是指向的值有可能变，所以依然不是线程安全 
</pre>
<pre>
<h4>27.针对以下代码，哪些说法是正确的：（） </h4>
class CompareReference{
   public static void main(String [] args){
   float f=42.0f;
   float f1[]=new float[2];
   float f2[]=new float[2];
   float[] f3=f1;
   long x=42;
   f1[0]=42.0f;
  }
}

A.f1==f2

B.x==f1[0]

C.f1==f3

D.f2==f1[1]

正确答案: B C   

BC正确，选项B解释，java核心卷I中43页有如下表述：两个数值进行二元操作时，会有如下的转换操作：
如果两个操作数其中有一个是double类型，另一个操作就会转换为double类型。
否则，如果其中一个操作数是float类型，另一个将会转换为float类型。
否则，如果其中一个操作数是long类型，另一个会转换为long类型。
否则，两个操作数都转换为int类型。
故，x==f1[0]中，x将会转换为float类型。
</pre>
<PRE>
<H4>28.关于中间件特点的描述.不正确的是（）</H4>
A.中间件运行于客户机/服务器的操作系统内核中，提高内核运行效率

B.中间件应支持标准的协议和接口

C.中间件可运行于多种硬件和操作系统平台上

D.跨越网络,硬件，操作系统平台的应用或服务可通过中间件透明交互

正确答案: A 

中间件是一种独立的系统软件或服务程序，分布式应用软件借助这种软件在不同的技术之间共享资源。中间件位于客户机/ 服务器的操作系统之上，
管理计算机资源和网络通讯。是连接两个独立应用程序或独立系统的软件。
相连接的系统，即使它们具有不同的接口，但通过中间件相互之间仍能交换信息。
执行中间件的一个关键途径是信息传递。通过中间件，应用程序可以工作于多平台或OS环境。
（简单来说，中间件并不能提高内核的效率，一般只是负责网络信息的分发处理）
</PRE>
<PRE>
static String str0="0123456789";
static String str1="0123456789";
String str2=str1.substring(5);
String str3=new String(str2);
String str4=new String(str3.toCharArray());
str0=null;
<H4>29.假定str0,...,str4后序代码都是只读引用。
Java 7中，以上述代码为基础，在发生过一次FullGC后，上述代码在Heap空间（不包括PermGen）保留的字符数为（）</H4>
A.5

B.10

C.15

D.20

正确答案: C   
substring实际是new，5字符
str3和4也都是new，每个5字符
分别都会创建新的对象
常量池是PermGen的
因此应该是一共15字符 
</PRE>
<PRE>
<H4>30.下面哪种情况会导致持久区jvm堆内存溢出？</H4>
A.循环上万次的字符串处理

B.在一段代码内申请上百M甚至上G的内存

C.使用CGLib技术直接操作字节码运行，生成大量的动态类

D.不断创建对象

正确答案: C 
简单的来说 java的堆内存分为两块:permantspace（持久带） 和 heap space。
持久带中主要存放用于存放静态类型数据，如 Java Class, Method 等， 与垃圾收集器要收集的Java对象关系不大。
而heapspace分为年轻带和年老带 
年轻代的垃圾回收叫 Young GC， 年老代的垃圾回收叫 Full GC。
在年轻代中经历了N次（可配置）垃圾回收后仍然存活的对象，就会被复制到年老代中。因此，可以认为年老代中存放的都是一些生命周期较长的对象
年老代溢出原因有  循环上万次的字符串处理、创建上千万个对象、在一段代码内申请上百M甚至上G的内存，既A B D选项
持久代溢出原因  动态加载了大量Java类而导致溢出 
</PRE>
<PRE>
<H4>31.下列关于JAVA多线程的叙述正确的是（）</H4>
A.调用start()方法和run()都可以启动一个线程

B.CyclicBarrier和CountDownLatch都可以让一组线程等待其他线程

C.Callable类的call()方法可以返回值和抛出异常

D.新建的线程调用start()方法就能立即进行运行状态

正确答案: C  

CyclicBarrier的字面意思是可循环使用（Cyclic）的屏障（Barrier）。
它要做的事情是，让一组线程到达一个屏障（也可以叫做同步点时被阻塞），直到最后一个线程到达屏障时，屏障才会开门，
所有被屏障拦截的线程才会继续执行。
CountDownLatch允许一个或多个线程等待其他线程操作完成。
</PRE>
<PRE>
<H4>32.以下集合对象中哪几个是线程安全的？( )</H4>
A.ArrayList

B.Vector

C.Hashtable

D.Stack

正确答案: B C D
在集合框架中，有些类是线程安全的，这些都是jdk1.1中的出现的。在jdk1.2之后，就出现许许多多非线程安全的类。 下面是这些线程安全的同步的类：
vector：就比arraylist多了个同步化机制（线程安全），因为效率较低，现在已经不太建议使用。在web应用中，特别是前台页面，往往效率（页面响应速度）是优先考虑的。
statck：堆栈类，先进后出
hashtable：就比hashmap多了个线程安全
enumeration：枚举，相当于迭代器
除了这些之外，其他的都是非线程安全的类和接口。 
</PRE>
<PRE>
<H4>33.关于PreparedStatement与Statement描述错误的是（）</H4>
A.一般而言，PreparedStatement比Statement执行效率更高

B.PreparedStatement会预编译SQL语句

C.Statement每次都会解析/编译SQL，确立并优化数据获取路径

D.Statement执行扫描的结果集比PreparedStatement大

正确答案: D
</PRE>
<PRE>
<H4>34.下面有关java final的基本规则，描述错误的是？</H4>
A.final修饰的类不能被继承

B.final修饰的成员变量只允许赋值一次，且只能在类方法赋值

C.final修饰的局部变量即为常量，只能赋值一次。

D.final修饰的方法不允许被子类覆盖

正确答案: B 
final修饰的成员变量为基本数据类型是，在赋值之后无法改变。当final修饰的成员变量为引用数据类型时，
在赋值后其指向地址无法改变，但是对象内容还是可以改变的。
final修饰的成员变量在赋值时可以有三种方式。1、在声明时直接赋值。2、在构造器中赋值。3、在初始代码块中进行赋值。 
</PRE>
<PRE>
<H4>35.java接口的方法修饰符可以为？(忽略内部接口)</H4>
A.private

B.protected

C.final

D.abstract

正确答案: D 
</PRE>
