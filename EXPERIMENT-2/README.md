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
}
```
#OUTPUT:
![OUTPUT OF exp-2a](2(a)output.png)
