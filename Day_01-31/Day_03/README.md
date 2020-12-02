# Day03 Java第一个程序HelloWord


1. 创建一个HelleWorld.java文件；
2. 添加如下代码：
    ```java
   class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
      }
   } 
    ```
3. 执行`javac HelloWorld.java`命令，编译成.class文件；
4. 通过`java HelloWorld`命令执行class文件，就会输出HelloWord;
   ```bash  
      % javac HelloWorld.java 
      % java HelloWorld
      Hello World
   ```