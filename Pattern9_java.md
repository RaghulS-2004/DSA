
## Problem-8:
Write a program to print the below pattern:
Input: 4

Output:
```
*
* *
* * *
* * * *
* * *
* *
*

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
        for(int i=1;i<=n;i++)
        {
            for (int j=1;j<=i;j++)
            {
                System.out.print("* ");
            }
            System.out.println();
        }
        for(int i=1;i<n;i++)
        {
            for(int j=1;j<=n-i;j++)
            {
                System.out.print("* ");
            }
            System.out.println();
        }
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/5bf3245d-c006-4e55-b7c0-e90e12fb1fa7)
