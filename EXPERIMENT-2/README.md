#EXPERIMENT-2
##exp 2a TITLE:to create class and methods
```java
class Square{
void area(int length){
System.out.println("area:"+length*length);
}
void perimeter(int length){
System.out.println("perimeter:"+4*length);
}
}
public class Main{
public static void main(String args[]){
Square obj=new Square();
obj.area(5);
obj.perimeter(6);
}
```
#OUTPUT:
![OUTPUT OF exp-2a](2(a)output.png)
##exp 2b TITLE:to implement method overloading
```java
class Mathoperation{
void add(int a,int b){
System.out.println("addition of 2 integers:"+(a+b));
}
void add(double a,double b){
System.out.println("addition of 2 double values:"+(a+b));
}
void add(int a,int b,int c){
System.out.println("addition of 3 integers:"+(a+b+c));
}
}
class Overloading{
public static void main(String args[]){
Mathoperation obj=new Mathoperation();
obj.add(2,5);
obj.add(2.56,3.56);
obj.add(1,5,6);
}
}
```
#OUTPUT:
![OUTPUT OF exp-2b](2(b)output.png)
##exp 2c TITLE:to implement constructor
```java
class Student{
String name;
int age;
double marks;
Student(String n,int a,double m){
name=n;
age=a;
marks=m;
}
void display(){
System.out.println("student name:"+name);
System.out.println("student age:"+age);
System.out.println("student marks:"+marks);
}
}
class Main{
public static void main(String args[]){
Student s1 =new Student("sireesha",19,95);
s1.display();
}
}
#OUTPUT:
![OUTPUT OF exp-2c](2(c)output.png)
