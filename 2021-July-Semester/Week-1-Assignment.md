## :hash: Week `1` Quiz

⭐ **1)** ***Which of the following cannot be used for a variable name in Java?***<br>
&emsp;&emsp;❑ **a.**  identifier<br>
&emsp;&emsp;❑ **b.**  case<br>
&emsp;&emsp;❑ **c.**  malloc<br>
&emsp;&emsp;❑ **d.**  calloc<br>
✔️ **Answer:&emsp;b**<br>
▸ **Explanation:** `Case` is a _reserved keyword_ in Java. Hence, we can't use it as a variable name. `identifier`, `malloc` and `calloc` are all valid variable names.<br>

⭐ **2)** ***Which of the following is an incorrect array declaration?***<br>
&emsp;&emsp;❑ **a.**  int[] b = new int[10];<br>
&emsp;&emsp;❑ **b.**  int [] b;<br>
&emsp;&emsp;❑ **c.**  int [][] b = new int[10];<br>
&emsp;&emsp;❑ **d.**  int [][] b = {{7, 2, 4, 6} , {9, 8, 5}};<br>
✔️ **Answer:&emsp;c**<br>
▸ **Explanation:**<br> `int [] arrayName = new int[size];` is most common way to declare an array.<br>
`int [] b;` is also correct as it declares the array without defining the size of the array.<br>
Option c is an incorrect way as `int[10]` is for declaration of an 1-D array but on the other side we have a 2-D array `int [][] b`. The correct way of declaration would be: `int [][] b = new int[10][];` or `int [][] b = new int[size][10];` where `size` is the number of rows in the 2-D array of our choice.
`int [][] b = {{7, 2, 4, 6} , {9, 8, 5}};` is also correct. It declares a 2-D array and also initializes it. The compiler gets the size of the array by counting the  number of elements in the array.

⭐ **3)** ***When you compile a program written in the Java programming language, the compiler converts the human-readable source file into platform-independent code that a `Java Virtual Machine` can understand. What is this platform-independent code called?***<br>
&emsp;&emsp;❑ **a.**  Source code<br>
&emsp;&emsp;❑ **b.**  Bytecode<br>
&emsp;&emsp;❑ **c.**  Machinecode<br>
&emsp;&emsp;❑ **d.**  Opcode<br>
✔️ **Answer:&emsp;**b<br>
▸ **Explanation:** When a Java program is executed, the compiler compiles that piece of code and a _Bytecode_ is generated for each method in that program in the form of a `.class` file. We can run this bytecode on any other platform as well. The bytecode generated after the compilation is run by the Java Virtual Machine.<br>

⭐ **4)** ***Which of the following is/are TRUE regarding the string array provided as a parameter to the main method in Java?***<br>
&emsp;&emsp;❑ **a.**  It can be used to get command line arguments from the user.<br>
&emsp;&emsp;❑ **b.**  It is mandatory to name the string array as 'args'.<br>
&emsp;&emsp;❑ **c.**  Only one command line argument input is allowed at a time.<br>
&emsp;&emsp;❑ **d.**  Both b and c.<br>
✔️ **Answer:&emsp;a**<br>
▸ **Explanation:** Through the string array passed as parameter to the `main` method, the arguments passed from the console can be received in the java program and it can be used as an input.<br>
We can name the string array with any valid name, like: `input`, `var123`, ... etc.<br>
Any number of arguments can be passed from the command like.
To compile> `javac className.java`<br>
To run> `java A B C 12345 xyz`<br>
To print the content of the `args` array we can traverse the arrat as:<br>
```java
for (int i=0; i<args.length; i++)
    System.out.println(args[i]);
```
If no argument is passed from the command line then an empty string `""` is passed by default.<br>

⭐ **5)** ***Consider the following program.***<br>
```java
public class Question
{
    public static void main(String args[])
    {
        for(int b=2; b<3; b+=2)
        {
            System.out.print(b+++b);
        }
    }
}
```
&emsp;&emsp;***What will be the output of the program if it is executed?***<br>
&emsp;&emsp;❑ **a.**  5<br>
&emsp;&emsp;❑ **b.**  2<br>
&emsp;&emsp;❑ **c.**  4<br>
&emsp;&emsp;❑ **d.**  1<br>
✔️ **Answer:&emsp;a**<br>
▸ **Explanation:** At b = 2, `b++ + b` = 2 + 3. After b++, b becomes 3. And at the end of the first iteration of th for loop,with `b += 2`, b becomes 3 + 2 = 5. As 5 is not less than 3, the `for` loop terminates.<br>

⭐ **6)** ***Following is a piece of code where some parts of a statement is missing:***<br>
```java
public class Question3
{
    public static void main(String args[])
    {
        char nptel[] = {'J','A','V','A','N','P','T','E','L'};
        System.out.print(__________);
    }
}
```
&emsp;&emsp;***In the following, some options are given. You have to choose the correct option for the argument in `System.outprint()` function to print the second and the last characters in the array `nptel`.***
&emsp;&emsp;❑ **a.**  nptel[nptel.length-1] + nptel[1]<br>
&emsp;&emsp;❑ **b.**  nptel[1] + nptel[nptel.length-1]<br>
&emsp;&emsp;❑ **c.**  "" + nptel[1] + nptel[nptel.length-11]<br>
&emsp;&emsp;❑ **d.**  "" + nptel[nptel.length-1] + nptel[1]<br>
✔️ **Answer:&emsp;**<br>
▸ **Explanation:**<br>

⭐ **7)** *** ***<br>
&emsp;&emsp;❑ **a.**  <br>
&emsp;&emsp;❑ **b.**  <br>
&emsp;&emsp;❑ **c.**  <br>
&emsp;&emsp;❑ **d.**  <br>
✔️ **Answer:&emsp;**<br>
▸ **Explanation:**<br>

⭐ **8)** *** ***<br>
&emsp;&emsp;❑ **a.**  <br>
&emsp;&emsp;❑ **b.**  <br>
&emsp;&emsp;❑ **c.**  <br>
&emsp;&emsp;❑ **d.**  <br>
✔️ **Answer:&emsp;**<br>
▸ **Explanation:**<br>

⭐ **9)** *** ***<br>
&emsp;&emsp;❑ **a.**  <br>
&emsp;&emsp;❑ **b.**  <br>
&emsp;&emsp;❑ **c.**  <br>
&emsp;&emsp;❑ **d.**  <br>
✔️ **Answer:&emsp;**<br>
▸ **Explanation:**<br>

⭐ **10)** *** ***<br>
&emsp;&emsp;❑ **a.**  <br>
&emsp;&emsp;❑ **b.**  <br>
&emsp;&emsp;❑ **c.**  <br>
&emsp;&emsp;❑ **d.**  <br>
✔️ **Answer:&emsp;**<br>
▸ **Explanation:**<br>

---
<p align="center">:heavy_plus_sign: <b>If you any <i>doubts/questions</i> related to this course or any <i>quiz/assignment</i>, <br>
please use the <a href="https://github.com/guru-shreyansh/NPTEL-Programming-in-Java/discussions"><i>Discussion Section</i></a>. 
I'll try to help at the earliest!!</b> :smiley:</p>
