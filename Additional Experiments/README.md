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
#ADDITIONAL EXPERIMENT-1
##exp-1 title:sub string into main string
```java
import java.util.Scanner;
class substring{
     public static void main(String args[]){
           String mainstring;
           String substring;
           int position;
           Scanner sc= new Scanner(System.in);
           System.out.println("enter the mainstring");
           mainstring= sc.nextLine();
           System.out.println("enter the substring");
           substring= sc.nextLine();
           System.out.println("enter the position to insert:");
           position= sc.nextInt();
           int length=mainstring.length()-1;
           String resultstring;
           if(position>=0&&position<=length){
             String firstpart =mainstring.substring(0,position);
             String secondpart =mainstring.substring(position);
             resultstring=firstpart+substring+secondpart;
             System.out.println("resulting string:"+resultstring);
             }
             sc.close();
             }
             }


```
#OUTPUT
![OUTPUT OF add-1](add1.png)
