![College logo](https://www.gndec.ac.in/sites/default/logo.png)

# Programming for Problem Solving(ESC-105)
--------------------
Submitted By-Dinbandhu Kumar

College Roll No: 1916089

University Roll No: 1905093

Branch: Electrical Engineering

Section: B

Batch: 2019-2023

--------
Experiment 1 : Write a code to print your name
```C
#include<stdio.h>
int main()
{
puts("Dinbandhu Kumar");
}
Output : 

Dinbandhu kumar
```

Experiment 2 : Write a practice program to display 'hello'.
```C
#include <stdio.h>
int main()
{
    puts("hello");
}

Output : 

hello
```
Experiment 3 : 
```C
#include <stdio.h>
int main()
{
    puts("########    ########     ####        ####");
    puts("##      ####        ####   ###     ###");
    puts("##      ####        ####     ###  ###");
    puts("######  ####        ####       ####");
    puts("##      ####        ####      ### ###");
    puts("##      ####        ####     ###    ###");
    puts("##          ########       ####       ####");
}
Output : 
########    ########     ####        ####                                       
##      ####        ####   ###     ###                                          
##      ####        ####     ###  ###                                           
######  ####        ####       ####                                             
##      ####        ####      ### ###                                           
##      ####        ####     ###    ###                                         
##          ########       ####       #### 
```
Experiment 4 : Write a C program to print a big ' C '.
```C
#include <stdio.h>
int main()
{
    puts(" ######");
    puts("##     ##");
    puts("#");
    puts("#");
    puts("#");
    puts("#");
    puts("#");
    puts("##     ##");
    puts("  ######");
}
Output : 
 ######                                                                         
##     ##                                                                       
#                                                                               
#                                                                               
#                                                                               
#                                                                               
#                                                                               
##     ##                                                                       
  ######                                                                        
```
Experiment 5 : Design a code to execute addition of two numbers.
```C
#include <stdio.h>
int main()
{
    int a,b,c;
    puts("enter two numbers");
    scanf("%d %d",&a,&b);
    c=a+b;
    printf("%d",c);
    return 0;
}
Output : 
enter two numbers                                                               
5 6                                                                             
11                                                                              
```
Experiment 6 : Write a computer program in C, which takes two numbers (integers) as input and print the smaller number.
```C
#include <stdio.h>
int main()
{
    int a,b;
    puts("enter the two number for comparison");
    scanf("%d %d",&a,&b);
    if(a<b)
    printf("the smaller number is %d",a);
    else
    printf("the smaller number is %d",b);
    return 0;
}
Output : 
enter the two number for comparison                                             
8 5                                                                             
the smaller number is 5                                                         
```
Experiment 7 : Write a C program to print the following character in a reverse way without using any predefined function and header file.
```C
#include <stdio.h>
int main()
{
    char ch1;
    char ch2;
    char ch3;
    scanf(" %c %c %c",&ch1,&ch2,&ch3);
    printf(" %c%c%c is %c%c%c",ch1,ch2,ch3,ch3,ch2,ch1);
    return 0;
}
Output : 
ram                                                                             
 ram is mar                                                                   
 ```
 Experiment 8 : Write a C program to compute the perimeter and area of a rectangle with a height of 7 inches and width of 5 inches.
```C
#include <stdio.h>
int main()
{
int height,width,perimeter,area;
    printf("Enter height and width: ");
    scanf("%d %d",&height,&width);
    perimeter=2*(height+width);
    printf("Perimeter of the rectangle: %d inches\n",perimeter);
    area=height*width;
    printf("Area of the rectangle = %d square inches\n",area);
    return 0;
}
Output : 
Enter height and width: 7 5                                                     
Perimeter of the rectangle: 24 inches                                           
Area of the rectangle = 35 square inches                                        
```
Experiment 9 :Design a code to execute addition of two numbers if the sum is even.Display a message Even otherwise Odd.
```C
#include <stdio.h>
int main()
{
    int a,b,c;
    puts("Enter two numbers");
    scanf("%d %d",&a,&b);
    c=a+b;
    if(c%2==0)
    printf("Even");
    else
    printf("Odd");
    return 0;
}
Output : 
Enter two numbers                                                               
4 5                                                                             
Odd                                                                             
```
Experiment 10 :  Design a code to mark 'Present' if student entered in a hall before 8:35 and
marked 'Late' before 8:45 otherwise marked 'Absent'.
If user will enter the time between 8:00 - 8:14 then display a message 'Sorry Gate closed' 
and if user  will enter the time less than 8:00 then display a message 'Its wrong Time'.
```C
#include <stdio.h>
int main()
{
   float time;
   scanf("%f",&time);
   if(time>8.14 && time<=8.36)
   printf("Present");
   else
   {  
      if(time>=8.36 && time<=8.45)
      printf("Late");
      else
      {
             if(time>8.45 && time<9.00)
             printf("Absent");
             else
             {
                 if(time==8.00 && time<=8.14)
                 printf("Sorry Gate closed");
                 else
                 {
                     if(time>7.00 && time<8.00)
                     printf("Its Wrong time");
                     else
                     {
                         if(time>=9.00)
                         printf("Sorry Gate closed");
                         else
                         {
                             if(time>=1.00 && time<=7.00)
                             printf("Its Wrong time");
                         }
                     }
                 }
             }
      }
   }   
}
Output : 
8.20                                                                            
Present                                                                         
```
Experiment 11 : Write a code to find the factorial of a number.
```C
#include<stdio.h>
int main()
{
    int n,i;
    long fact = 1;
    printf("Enter an integer: ");
    scanf("%d",&n);
    if(n < 0)
    printf("Error! Factorial of a negative number does not exist.");
    else
       {
           for (i = 1; i<=n; i++)
           fact =fact * i;
           printf("%d = %ld",n,fact);
       }
       return 0;
}
Output : 
Enter an integer: 5                                                             
5 = 120                                                                         
```
