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




