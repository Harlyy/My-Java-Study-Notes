# **2 开发体验 Hello World**

**2.1 Hello World**

```java
public class test {
        public static void main(String[] args){
			System.out.print("Hello World!");
        }
}
```

进入DOS运行：

![1587478652718](C:\Users\-\AppData\Roaming\Typora\typora-user-images\1587478652718.png)

进入java程序文件所在文件夹 → 输入javac+空格+文件名（加扩展名） → 回车

**如何查看是否成功编译完成：**进入源文件夹，看是否出现.class文件。

然后，在DOS界面输入java+空格+文件名（不加扩展名，**但此时运行的是.class文件**） → 空格

运行结果如下：

![1587478890986](C:\Users\-\AppData\Roaming\Typora\typora-user-images\1587478890986.png)

------

**程序小结：**

- Java源文件都是以"java"为扩展名，源文件的基本组成部分是类（class），例如本程序中的test就是一个class。
- java应用程序的执行入口时main()方法，它有固定的书写格式，即：public static void main(String[] args){......}
- Java语言严格区分大小写。
- Java程序由一条条语句组成，每个语句以";"（**注意：英文分号**）结束。
- **括号都是成对出现的**



**常见问题：**

![1587479744686](C:\Users\-\AppData\Roaming\Typora\typora-user-images\1587479744686.png)

- 源文件名不存在或者写错，或者当前路径错误。

![1587479768981](C:\Users\-\AppData\Roaming\Typora\typora-user-images\1587479768981.png)

- 类文件名写错，或者类文件不在当前路径下，或者不再classpath指定路径下。

![1587480018860](C:\Users\-\AppData\Roaming\Typora\typora-user-images\1587480018860.png)

- 声明为public的主类应与文件名一致，否则编译失败。

![1587480060253](C:\Users\-\AppData\Roaming\Typora\typora-user-images\1587480060253.png)

- 编译失败，注意错误出现的行数，再到源代码中的指定行改错。