## BASIC - 2 (JAVA)
## Problem-1:
Write a program which takes two values x and y. Prints x for y number of times.

Input:

2 

3

Expected Output

2

2

2

Explanation - 2 is x and 3 is y in the input. So 2 is printed 3 times on the output.

## PROGRAM:(Main.java)
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        int x = input.nextInt();
        int y = input.nextInt();
        for(int i=0;i<=y;i++)
        {
            System.out.println(x);
        }
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/a98cd18e-78c4-48e4-a43d-fc22eb76875c)   

## Problem-2:
Write a program to take x and print multiples of x till 1000.

Input:

100

Expected Output:

100

200

300

400

500

600

700

800

900

1000

Explanation - Input is 100, multiples of 100 is 100*1, 100*2, 100*3 and so on till 1000.

## PROGRAM:(Main.java)
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        System.out.print("Enter a number : ");
        int num = input.nextInt();
        for(int i=1;i*num<=1000;i++)
        {
            System.out.println(i*num); 
            
            
        }
        
    }
}
```

## OUTPUT
![image](https://github.com/user-attachments/assets/8e688248-a076-4659-826f-c75e9fce61f7)

## Problem-3:

Write a program to get firstName and lastName and n as input and print fullName that is firstName+lastName for n times.

Input

Nandy

Raja

5

Expected output:

NandyRaja

NandyRaja

NandyRaja

NandyRaja

NandyRaja

Explanation - Nandy is the firstName, Raja is the lastName and n is 5, so the expected output has NandyRaja printed 5 times.

## PROGRAM:(Main.java)
```
import java.util.*;
public class Main
{
    public static void main(String[] args)
    {
        Scanner input=new Scanner(System.in);
        String first_name=input.next();
        String last_name=input.next();
        int num=input.nextInt();
        for (int i=0;i<num;i++)
        {
            System.out.println(first_name+last_name);
        }
        
    }
}
```
## OUTPUT 
![image](https://github.com/user-attachments/assets/457be14a-4184-4361-a8a3-1e2f2eb9a0eb)
