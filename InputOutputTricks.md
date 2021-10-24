Input Output Tricks On Java
===========================
# *1. Continuous input*
-------------------------
## /*
## ** input: 1, 3, 5, 7, 9, 11 , ... 
## ** output: calculating the sum of this sequence
#  */
### Code

```java
import java.util.*;
public class Main {
  public static void main(String[] args) {
      Scanner sc = new Scanner(System.in);
      while (sc.hasNext()) {
    // Add your own operation here (添加你的操作)
    
      }
   }

}
```
# *2. Limited size of inputs*
-------------------------
## /* calculating the sum of the given size sequence
## ** input: 5, [1, 1, 2, 2, 3]  ... 
## ** output: 9
#  */
### Code
```java
import java.util.*;
public class Main {
  public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
    int n = sc.nextIn();
    while (n > 0) {
    // Add your own operation here (添加你的操作)
    
      n--;
    }
   }
}
```
# *3. Multiple info in a single line, use Split to tokenize*
-------------------------
## /* 
## ** input: a c bb ccc d ee
## ** output: Unknown output
#  */
### Code
```java
import java.util.*;
public class Main {
  public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
    while (sc.hasNext()) {
    // Split into a String Array
      String[] strArray = sc.nextLine().split(" ");
    // Add your own operation here (添加你的操作)
   
    }
   }
}
```
# *4. When input contains an End sign*
-------------------------
## /* Calculating sum, 0 as an end
## ** input: 4 1 2 3 4 (sum of 4 numbers: 1+2+3+4)
## **        5 1 2 3 4 5
## **        0         (end of input)
## ** output: Unknown output
#  */
### Code
```java
import java.util.*;
public class Main {
  public static void main(String[] args) {
    Scanner sc = new Scanner(System.in);
    int n = sc.nextInt();
    if (n == 0) {
      return;
    }
    int sum = 0;
    while (n > 0) {
      sum += sc.nextInt();
    }
   }
}
```
