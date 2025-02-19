## BASIC - 1 (JAVA)
## Problem-1:
Write a program that takes an integer, then a string, then a char from the user and prints them in the screen.

Input:  2 Name y

Expected Output:

2

Name

y

## PROGRAM:(Main.java)
```
import java.util.Scanner;
public class Main
{
    public static void main(String[] args)
    {
        int num;
        String name;
        char ch;
        Scanner input=new Scanner(System.in);
        num=input.nextInt();
        name=input.next();
        ch=input.next().charAt(0);
        System.out.println(num);
        System.out.println(name);
        System.out.println(ch);

    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/c9d58f12-d25a-4f6d-a62a-9ab1b785e555)

