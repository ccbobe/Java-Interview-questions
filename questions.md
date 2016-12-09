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
