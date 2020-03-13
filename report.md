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
