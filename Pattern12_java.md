
## Problem-12:
Write a program to print the below pattern:
Input: 4

Output:
```
      *
    * * *
  * * * * *
* * * * * * *
  * * * * *
    * * *
      *

```

## PROGRAM:(Main.java)
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner input= new Scanner(System.in);
        int n=input.nextInt();
        for(int i=1;i<=n;i++)
        {
            for(int j=1;j<=(n-i);j++)
            {
                System.out.print("  ");
            }
            for(int j=1;j<=(2*n)-(2*n - ((2*i)-1));j++)
            {
                System.out.print("* ");
            }
            System.out.println();
        }
        for(int i=1;i<n;i++)
        {
            for(int j=1;j<i+1;j++)
            {
                System.out.print("  ");
            }
            for(int j=1;j<=(2*n - ((2*i)+1));j++)
            {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/3d324648-a074-4304-9f5d-4246e904fe48)
