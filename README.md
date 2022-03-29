# java

## What is Java?
#### Java is a programming language and a platform. Java is a high level, robust, object-oriented and secure programming language.

## Install jdk
#### Install JDK Click this link https://www.oracle.com/java/technologies/downloads/

## Java basic program

```java
Class basic{
           Public static void main(string args[]){
           System.out.println(“Hello java”);
           }
}
```

## Command line argument in java

```java
class basic{
    public static void main(String args[]){
         for(int i=0; i<args.length; i++){
                 System.out.println(args[i]);
        }
}
}
```
## Multi and single line command in java
### Single line command ```// command ```
### Multi line commend ```/* command */ ```

## variables in java

```java
    public static void main(String args[]){
         String name = "Prasanna venkatesh";
         int age = 21;
         Float percentage = 78.7f;
         char gender = 'M';
         Boolean married = false;
         System.out.println("name : " + name);
         System.out.println("age : " + age);
         System.out.println("percentage : " + percentage);
         System.out.println("gender : " + gender);
         System.out.println("married  : " + married);
        }
   }
```
## Types of casting in java
### Widening casting
``` byte -> short -> char -> int -> long -> float -> double ```
### Narrow casting
``` Double -> float -> long -> int -> char -> short -> byte ```
```java
class basic{
    public static void main(String args[]){
        int a = 10;
        double b = a, c = 25.456;
        int d = (int)c;
        System.out.println("int : " + a);
        System.out.println("double : " + b);
        System.out.println("double : " + c);
        System.out.println("int : " + d);
       }
  }
 ```
 
 ## Arithmetic operator in java 
 
 ```java
class basic{
    public static void main(String args[]){
        int a = 10, b=20;
        System.out.println("Add : " + (a+b));
        System.out.println("multi : " + (a*b));
        System.out.println("Sub : " + (a-b));
        System.out.println("div : " + (a/b));
        System.out.println("modular : " + (a%b));
       }
  }
```

## Arithmetic assignment operator in java 

```java
class basic{
    public static void main(String args[]){
        int a = 10;
        System.out.println(a);
        a += 10;
        System.out.println(a);
        a -= 10;
        System.out.println(a);
        a *= 10;
        System.out.println(a);
        a /= 10;
        System.out.println(a);
        a %= 10;
        System.out.println(a);
       }
  }
```

## relational oprator in java 

``` java 
class basic{
    public static void main(String args[]){
        int a = 100, b=24;
        System.out.println("Equal to "+ (a==b));
        System.out.println("less than "+(a<b));
        System.out.println("grater than "+(a > b));
        System.out.println("not equal than "+(a != b));
        System.out.println("less than or equal to "+(a <= b));
        System.out.println("grater than or equal to "+(a >= b));
       }
  }
  ```
  ## logical operator in java 
```java 
class basic{
    public static void main(String args[]){
        int a = 100, b=24;
        System.out.println("And && "+ (a>b && a>b));
        System.out.println("or || "+ (a>b || a>b));
       }
  }
  ```
  
 
 ## Conditional and ternary operator in java
 
 ```java
class basic{
    public static void main(String args[]){
        int a = 100, b=24,c;
        c=a>b?a:b;
        System.out.println("The greatest number is"+ c);
        int d = 100, e=24,f;
        f=d<e?d:e;
        System.out.println("The lowest number is"+ f);
       }
  }
  ```

## Unary operator in java 

```java
class basic{
    public static void main(String args[]){
        int a = 10;
        System.out.println(a);
            a++; //post increment
        System.out.println(a);
            ++a; //pre increment
        System.out.println(a);
            a--; //post decrement
        System.out.println(a);
            --a; //pre decrement
        System.out.println(a);
       }
  }
  ```
  ## bitwise or shift operators in java
  
  ```java
class basic{
    public static void main(String args[]){
        int a=2,b=3;
        System.out.println("bitwise and " + (a&b));
        System.out.println("bitwise or " + (a|b));
        System.out.println("bitwise Xor " + (a^b));
        System.out.println("bitwise not " + (~a));
       }
  }

  ```
  
  ## Scanner class
  
  ```java
import java.util.Scanner;

public class basic{
    public static void main(String args[]){

        Scanner in = new Scanner(System.in);
        //a2+b2+2ab
        int a,b,c;
        a=in.nextInt();2
        b=in.nextInt();
        c=(a*a)+(b*b)+(2*a*b);

        System.out.println(c);
       }
  }
  ```

## If statement

```java
import java.util.Scanner;

public class basic{
    public static void main(String args[]){

        Scanner in = new Scanner(System.in);
        int a;
        System.out.println("Enter value for a :");
        a=in.nextInt();
        if(a>=17){
            System.out.println("You are eligible for apply");
        }
       }
  }
  ```
  
  ## If-else statement
  
  ```java
import java.util.Scanner;

public class basic{
    public static void main(String args[]){

        Scanner in = new Scanner(System.in);
        int a;
        System.out.println("Enter value for a :");
        a=in.nextInt();
        if(a>=17){
            System.out.println("You are eligible for apply");
        }else{
            System.out.println("You are not eligible for apply");
       }
  }}

```

## else-if statement

```java
import java.util.Scanner;

public class basic{
    public static void main(String args[]){
        Scanner in = new Scanner(System.in);
        float a;
        System.out.println("Enter your mark :");
        a=in.nextfloat();
        if(a>=90 && a<=100){
            System.out.println("grade A");
        }else if(a>=80 && a<=89){
            System.out.println("Grade B");
       }else if(a>=70 && a<=79){
            System.out.println("Grade C");
       }else{
            System.out.println("Grade D");
       }
  }
  }
  ```

## Nested if statement
```java
import java.util.Scanner;
public class basic{
    public static void main(String args[]){
        Scanner out = new Scanner(System.in);
        System.out.println("Enter your marital status :");
        char ele = out.next().charAt(0);

        if(ele == 'u' || ele == 'U'){
            System.out.println("Male/Female :");
            char gender = out.next().charAt(0);
            if(gender == 'f' || gender == 'F'){
                System.out.println("Enjoy your life doli");
            }else {
                System.out.println("Enjoy your life tholare");
            }
           
        }else if(ele == 'm' || ele == 'M'){
            System.out.println("lifefa tholachitiya pangu");
        }else{
            System.out.println("Bee happy and safe");
        }
  }}
```

## Switch case statement

```java
import java.util.Scanner;
public class basic{
    public static void main(String args[]){
        System.out.println("Enter 1 is Addition :");
        System.out.println("Enter 2 is subtraction :");
        System.out.println("Enter 3 is multiplication :");
        System.out.println("Enter 4 is deviation :");
        System.out.println("Enter your choice :");
        int a,b,ch;
        Scanner output = new Scanner(System.in);
        ch = output.nextInt();
        System.out.println("Enter 2 numbers :");
        a=output.nextInt();
        b=output.nextInt();
        switch(ch){
            case 1:
                    System.out.println("Enter 1 is Addition :" +(a+b));
                    break;
            case 2:
                    System.out.println("Enter 2 is subtraction :" + (a-b));
                    break;
            case 3:
                    System.out.println("Enter 3 is multiplication:"+(a*b));
                    break;
            case 4:
                    System.out.println("Enter 4 is deviation :" + (a/b));
                    break;
            default:
                    System.out.println("invalid selection");
                    break;
            }
          }
        }
```

## Group switch case statement
```java
import java.util.Scanner;
public class basic{
    public static void main(String args[]){
        char a;
        Scanner output = new Scanner(System.in);
        System.out.println("Enter letter :");
        a = output.next().charAt(0);
        switch(a){
        case 'a':
        case 'e':
        case 'i':
        case 'o':
        case 'u':
        case 'A':
        case 'E':
        case 'I':
        case 'O':
        case 'U':         
        System.out.println(a+" is vowel");
        break;
        default:
        System.out.println(a+" is not vowel");
        break;
}}}
```

