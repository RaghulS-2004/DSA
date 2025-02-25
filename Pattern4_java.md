
## Problem-4:
Write a program to print the below pattern:
Input: 4

Output:
```
* ** *** ****
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
            System.out.print(" ");
        }
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/99c2ee3d-4a66-40f7-9c34-4033164a5a8a)
