
## Problem-7:
Write a program to print the below pattern:
Input: 4

Output:
```
4321
321
21
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
            for(int j=num-i+1;j>0;j--)
            {
                System.out.print(j);
            }
            System.out.println();
        }
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/5277f228-5a56-4e56-b0af-3eb71bfcbf24)
