
## Problem-14:
Write a program to print the below pattern:
Input: 8

Output:
```
1 
2 2 
3 3 3 
4 4 4 4 
5 5 5 5 5 
6 6 6 6 6 6 
7 7 7 7 7 7 7 
8 8 8 8 8 8 8 8 

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
        int count=1;
        for(int i=1;i<=n;i++)
        {
            for(int j=1;j<=i;j++)
            {
                System.out.print(count);
                System.out.print(" ");
                
            }
            count+=1;
            System.out.println();
        }
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/ba5cb35b-ea9a-4889-95e7-c7796623ca78)
