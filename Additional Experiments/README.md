#ADDITIONAL EXPERIMENT-2
##exp 2 title:fibonacci series
```java
import java.util.scanner;
class  fibbonacci{
int sum;
int n;
int firstnumber;
int secondnumber;
int thirdnumber;
fibbonacci(int number){
n=number;
firstnumber=0;
secondnumber=1;
thirdnumber=0;
sum=0;
}
void generate(){ if(n>0){ 
System.out.println("Fibbonacci series");
while(n>0){
if(n==1){
System.out.println(firstnumber+".");
sum=sum+firstnumber;
}
thirdnumber=firstnumber+secondnumber;
firstnumber=secondnumber;
secondnumber=thirdnumber;
n--;
}
System.out.println("sum of fibbonacci series");
}

}
```
#OUTPUT
![OUTPUT OF add-2](add2.png)
