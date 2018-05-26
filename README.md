# LogicPatterns
> Print 


```java   

/*
Java
 ava
  va
   a
 */
import java.util.*;
public class MyClass {
    public static void main(String args[]) {
        String s="Java";
        
        for(int i=0;i<4;i++){
            for(int j=0;j<4;j++){
                
                if(j>=i){
                     System.out.print(s.charAt(j));
                }
                else{
                     System.out.print(" ");
                }
               
                
            }
            System.out.println();
            
        }
    }
}

```

> guess Output `int i=010; System.out.print(i);`

```java
output : 8//because when you put 0 infront of number it will convert to octal number

```
