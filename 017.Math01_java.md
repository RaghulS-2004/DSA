## Mathematical Concepts
## Problem-1:
Write a program that gets n as input and print the number of digits in the number
```
Testcase 1 :

Input : 

325345

Expected output:

6
```
```
Testcase 2 :

Input : 

9879

Expected output:

4
```

## PROGRAM:(Main.java)
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        int n=input.nextInt();
        int count=0;
        while(n>0)
        {
            int last=n%10;
            n=n/10;
            count+=1;
        }
        System.out.println(count);
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/78c5d78a-544c-460f-bd00-657b51461105)
