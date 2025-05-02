# EX-06 - Looping
## AIM:
Write a C Program to print  even numbers ranging from M to N (including M and N values) in reverse order.

## ALGORITHM:
1.	Declare two integer variables to store the values of x and y.	
2.	Use the scanf function to read the values of x and y from the user.
3.	Use a loop (for or while) to iterate from y to x in reverse.
4.	Inside the loop, check if the current number is even.
5.	If the current number is even, print it.
6.	Continue the loop until you have iterated through all numbers from y to x.

## PROGRAM:

#include<stdio.h>

int main()

{

    int x,y;
    
    scanf("%d %d",&x,&y);
    
    while (y>=x)
    
    {
    
        if (y%2==0)
        
        {
        
            printf("%d ",y);
            
            
            
        }
        
        y--;
        
        
    }
    
 
    return 0;
    
}
## OUTPUT:

![image](https://github.com/user-attachments/assets/9e9766a8-1a3c-400b-a26c-f4ee99cab615)










## RESULT:
Thus the program to print even numbers ranging from M to N (including M and N values) in reverse order has been executed successfully
 
 


# EX-07-Nested-loop

## AIM:

Write a C program to print the given triangular pattern using loop.

## ALGORITHM:

1.	Declare a variable to store the number of rows in the triangle.
2.	Use the scanf function to read the number of rows from the user.
3.	Use a loop (for or while) to iterate through each row.
4.	Inside the loop, use another loop to print the desired number of dollar symbol for each row.
5.	Continue the loop until you have printed the entire triangular pattern.

## PROGRAM:

#include <stdio.h>

int main() {

   int i, j, rows;
   
   scanf("%d", &rows);
   
   for (i=rows; i >= 1; i--) 
   
   {
   
      for (j = 1;j<=i ;j++)
      
      {
      
         printf("$");
         
      }
      
      printf("\n");
      
   }
   
   return 0;
   
}
## OUTPUT:

![image](https://github.com/user-attachments/assets/3e32afd8-5c1d-415d-bed0-024932384bea)




## RESULT:

Thus the program to print the given triangular pattern using loop has been executed successfully.
 
 


# EX-08-Functions

## AIM:

Write a C program to perform addition and subtraction of two numbers using functions (with argument and without return type).

## ALGORITHM:

1.	Declare two functions, one for addition and one for subtraction. Both functions should take two integer arguments.
2.	Inside the addition & subtraction function, add & subtract the two numbers and print the result.
3.	In the main function, declare two integer variables and read their values from the user.
4.	Call the addition and subtraction functions, passing the two numbers as arguments.

## PROGRAM:

#include<stdio.h>

void add(int a,int b)

{

    int r;
    
    r=a+b;
    
    printf("Addition: %d",r);
    
}

void sub(int a,int b)

{

    int s;
    
    s=a-b;
    
    printf("\nSubtraction: %d",s);
    
}

int main()

{

    int m,n;
    
    scanf("%d",&m);
    
    scanf("%d",&n);
    
    add(m,n);
    
    sub(m,n);
    
    return 0;
    
}
## OUTPUT:

![image](https://github.com/user-attachments/assets/13037a79-b8a0-4c79-a771-d3938c8f2d81)





## RESULT:

Thus the program to perform addition and subtraction of two numbers using functions has been executed successfully
 
 


# EX-09-Use For Loop

## AIM:

Write a c program to find the sum of even digits using for loop.

## ALGORITHM:

1.         Start the program and declare three integer variables: x, s (sum), and i (loop counter).
2.         Take input from the user for an integer x.
3.         Use a for loop to go through all even numbers from 2 up to x.
4.         In each loop iteration, add the even number to the sum s and print the number.
5.         After the loop, print the total sum of the even numbers and end the program.



## PROGRAM:

#include<stdio.h>

int main()

{

    int x,s=0,i;
    
    scanf("%d",&x);
    
    for(i=2;i<=x;i+=2)
    
    {
    
        s+=i;
        
        printf("%d  ",i);
        
        
        
    }
    
    printf("\n%d",s);
    
    return 0;
    
    
}

## OUTPUT:

![image](https://github.com/user-attachments/assets/838c08c8-d68b-4c35-bf6e-c9506965bb41)



## RESULT:

Thus the program to find the sum of even digits using for loop has been executed successfully.




# EX – 10 - Factorial of a Number Using a Function
## AIM:
Write a C program for finding the factorial of a given number using function with return type with arguments.


## ALGORITHM:

1.        Start the program and declare a function fact to calculate factorial.

2.        In the main function, declare an integer m and take input from the user.

3.        Call the fact function, passing the input number m as an argument.

4.        Inside the fact function, use a loop to multiply numbers from 1 to a to compute the factorial.

5.        Print the factorial result and return from the function, then end the program.



## PROGRAM:

#include <stdio.h>

int fact (int);

int main()

{

    int m;
    
    scanf("%d",&m);
    
    fact(m);
    
    return 0;
    
}

int fact(int a)

{

    int f=1,i;
    
    for(i=1;i<=a;i++)
    
    {
    
        f=f*i;
        
    }
    
    printf("Factorial value is: %d",f);
    
    return 0;
    
}
 
## OUTPUT:

![image](https://github.com/user-attachments/assets/5105ccc4-5731-4129-ba39-9d5cba7e0bd2)








## RESULT:
The program correctly computes the factorial of a given number using a separate function and displays the result.
 
