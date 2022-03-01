# java-foundation
Introduction:
JavaSE标准版。
JavaEE 企业级开发。
JDK: Java development kit. Include JRE.
JRE: Java runtime environment.
JVM: Java virtual machine.

Demo 1 Hello world

public class Hello {
    public static void main(String[] args) {
        System.out.println("Hello, World! ");
    }
}




coding fundation:
Notes
Three types of notes:
single line note:
multiple notes:
doc notes:


Identifiers and Keywords


data type extension


data type conversion


variable, constant, scope


basic operator


string connector +:
System.out.println(a+b+"");
String at back, the parameters will be executed and the "" will be ignored.
System.out.println(""+a+b);
String at first, the parameters will be combined.

x ? y : z 
If X is true, then the result is Y, if the x is false, then the result is z.
example: 
int score = 80;
String type = score < 80?"Pass":"Fail"


Flow control
Scanner
scanner.close();
I/O flow like scanner, must be shutted down after using. Cauz it takes resources.

scanner.hasNext() Use blank as the finish mark. cannot get string with blank
scanner.hasNextLine()  Use enter as finish mark. get all.

Structure

break and continue
























