
## Problem-1:
Write a program to print the below pattern:
Input: 4

Output:
```
1
12
123
1234
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
                System.out.print(j);
            }
            System.out.println();
        }
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/6919c2b0-0834-4f20-9bf1-7db076ebfd80)
