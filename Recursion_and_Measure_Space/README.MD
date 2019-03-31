# Recursion & Measure Space
## Summation of N odd numbers
- Create two Java programs to calcultae the summation of N odd numbers. One is a recursive version, the other is an iterative version.
- Please compare the performance of these two programs by calculating
- 9999 + 9997 + .... + 3 + 1

## Java program space complexity (method and static variable)
```java
public class Test 
{ 
    static int x = 11; 
    private int y = 33; 
    public void method1(int x) 
    { 
        Test t = new Test(); 
        this.x = 22; 
        y = 44; 
  
        System.out.println("Test.x: " + Test.x); 
        System.out.println("t.x: " + t.x); 
        System.out.println("t.y: " + t.y); 
        System.out.println("y: " + y); 
    } 
  
    public static void main(String args[]) 
    { 
        Test t = new Test(); 
        t.method1(5); 
    } 
} 
```
### Questions:
- Please determine the bytecode size of the following Java program
- Please calculate the minimum RAM size required to run this Java program.

## C Program space complexity
```java
int i =2;
void f(int j) {
  j = i + 2;
}
void main()
{
   int k = 3;
   static c = '4';

   {
      int m = i;
   }
   f(k);
}
```
### Questions:
- Please determine the executable code size
- Please calculate the minimum RAM size required to run this C program on a 32-bit machine
