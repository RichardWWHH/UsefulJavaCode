Function tricks:
================
Trim and Concatination
----------------------
# Note: 
## 使用nextLine()方法
### next() vs nextLine()
### next():
#### 1. 一定要读取到
``` Java
import java.util.*;
public class Main {
  public static void main(String[] args) {
    String[] strArr = sc.nextLine().split(" ");
    Arrays.sort(strArr);
    for (String s : strArr) {
      res += s + " ";
    }
    System.out.println(res.trim());
  }  
}
```
