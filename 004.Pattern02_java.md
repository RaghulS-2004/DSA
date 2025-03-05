
## Problem-1:
Write a program to print the below pattern:
Input: 4

Output:
```
1234
1234
1234
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
            for(int j=1;j<=num;j++)
            {
                System.out.print(j);
            }
            System.out.println();
        }
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/d6b47079-ca3a-42b2-827f-79282e5436ce)

