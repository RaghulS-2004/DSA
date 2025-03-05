
## Problem-5:
Write a program to print the below pattern:
Input: 4

Output:
```
1234
123
12
1
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
                System.out.print(j);
            }
            System.out.println();
        }
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/8fb646a0-bbd5-45f5-8c13-e37a00b93f1a)
