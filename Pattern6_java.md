
## Problem-6:
Write a program to print the below pattern:
Input: 4

Output:
```
****
***
**
*

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
            for(int j=1;j<=num-i+1;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/3a47c2a5-6185-4f93-9bbe-a4884cafab12)
