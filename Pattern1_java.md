
## Problem-1:
Write a program to print the below pattern:
Input: 4

Output:
```
****
****
****
****
```

## PROGRAM:(Main.java)
```
import java.util.*;
class Main {
    public static void main(String[] args) {
        Scanner input =  new Scanner(System.in);
        int num = input.nextInt();
        for(int i=0;i<num;i++)
        {
            for(int j=0;j<num;j++)
            {
                System.out.print("*");
            }
            System.out.println();
        }
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/b5bb0d18-ad01-4433-8960-2a1ff956a2ae)
