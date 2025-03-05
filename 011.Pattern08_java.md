
## Problem-8:
Write a program to print the below pattern:
Input: 4

Output:
```
*
**
***
****

```

## PROGRAM:(Main.java)
```
import java.util.*;
class Main {
    public static void main(String[] args) {
        Scanner input =  new Scanner(System.in);
        int num = input.nextInt();
        for(int i=1;i<=num;i++)
        {
            for(int j=1;j<=i;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/9a1f1e74-7cf7-40fa-a9d9-1d4ba5e449ab)
