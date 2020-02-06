----
[![logo.png](https://i.postimg.cc/fLGF48bp/logo.png)](https://postimg.cc/dk9nrmrj)
----

# PROGRAMMING FOR PROBLEM SOLVING ESC-18105
----

* ***NAME- ___________________*** 

     [![mine.jpg](https://)](https://)

* ***CLASS ROLL NO.-_________***   
* ***COLLEGE ROLL NO.-____________***
* ***BRANCH- INFORMATION TECHNOLOGY***
* ***SECTION- _____***
* ***SUBMITTED TO- Jagdeep Singh***
----

# 
# PROGRAMES
----
***Q1.Program to add two numbers.***
```C
#include <stdio.h>
int main()
{
  int x, y, z;

  printf("Enter two numbers to add\n");
  scanf("%d%d", &x, &y);

  z = x + y;
    
  printf("Sum of the numbers = %d\n", z);

  return 0;
}
```
***OUTPUT***
```
Enter two numbers to add:                                                                                                       
7                                                                                                                               
9                                                                                                                               
Sum of the numbers = 16 
```
***Q2.Display college address using puts.***
```C
#include<stdio.h>
int main()
{

puts("Principal");
puts("Panth Rattan Shiri Gurcharan Singh Tohra Complex");
puts("Guru Nanak Dev Engineering College");
puts("Gill Park");
puts("Ludhiana - 141006");
puts("India");
  }
```
***OUTPUT***
```
Principal                                                                                                                     
Panth Rattan Shiri Gurcharan Singh Tohra Complex                                                                              
Guru Nanak Dev Engineering College                                                                                            
Gill Park                                                                                                                     
Ludhiana - 141006                                                                                                             
India
```

***Q3.Program to write N number times "I will switch off lights, fans and Ac when leaving room".***
```C
#include<stdio.h>
int main()
{
int a;
printf("ENTER THE NUMBER:");
scanf("%d",&a);
for ( int i = 1; i <= a; i++ )
printf(" \nI will switch off lights, fans and AC when leaving room");
}
```
***OUTPUT***
```
ENTER THE NUMBER :6                                                                                                       
                                                                                                                              
I will switch off lights, fans and AC when leaving room                                                                       
I will switch off lights, fans and AC when leaving room                                                                       
I will switch off lights, fans and AC when leaving room                                                                       
I will switch off lights, fans and AC when leaving room                                                                       
I will switch off lights, fans and AC when leaving room                                                                       
I will switch off lights, fans and AC when leaving room
```
***Q4.Convert temperature from Farenheit to Centigrade scale.***
```C
#include<stdio.h> 
int main()
{
printf("Enter temperature in fahrenheit:");
float f,c=0;
scanf("%f",&f);
c=(5.0/9)*(f-32.0);
printf("Temperature in centigrade:%f\n",c);
} 
```
***OUTPUT***
```
Enter temperature in fahrenheit:56                                                                                            
Temperature in centigrade:13.333333
```
***Q5.Check whether the number is even or odd.***
```C
#include<stdio.h>
int main()
{
int i;
printf("Enter the Number:");
scanf("%d",&i);
if (i%2==0)
printf("Number is Even\n");
else
printf("Number is Odd\n");
} 
```
***OUTPUT***
```
Enter the Number:7                                                                                                            
Number is Odd 

Enter the Number:4                                                                                                            
Number is Even 
```
***Q6.Print half pyramid using *.***
```C
#include<stdio.h>
int main()
{
int n,i,j;
printf("Enter desired number");
scanf("%d",&n);
for (i=1;i<=n;i++)
{
for(j=1;j<=i;j++)
{
printf("*");
}
printf("\n");
}
}
```
***OUTPUT***
```
Enter desired number7                                                                                                         
*                                                                                                                             
**                                                                                                                            
***                                                                                                                           
****                                                                                                                          
*****                                                                                                                         
******                                                                                                                        
*******
```
***Q7.Finds the factorial of a number *.***
```C
#include <stdio.h>
 
int main()
{
  int c, n, f = 1;
 
  printf("Enter a number to calculate its factorial\n");
  scanf("%d", &n);
  for (c = 1; c <= n; c++)
    f = f * c;
 
  printf("Factorial of %d = %d\n", n, f);
 
  return 0;
}
```
***OUTPUT***
```
Enter a number to calculate its factorial                                                                                     
6                                                                                                                             
Factorial of 6 = 720 
```
***Q8.Display the table of user's choice.***
```C
#include<stdio.h>
int main()
{ 
printf("Enter Number");
int n;
scanf("%d",&n);
int i;
for(i=1;i<=10;i++)
{
printf("%d x %d = %d\n",n,i,n*i);
}
}
```
***OUTPUT***
```
Enter Number3                                                  
3 x 1 = 3                                                      
3 x 2 = 6                                                      
3 x 3 = 9                                                      
3 x 4 = 12                                                     
3 x 5 = 15                                                     
3 x 6 = 18                                                     
3 x 7 = 21                                                     
3 x 8 = 24                                                     
3 x 9 = 27                                                     
3 x 10 = 30
```
***Q9.Display the table of two desired number.***
```C
#include<stdio.h>
int main()
{ 
printf("Enter 1st Number");
int n1;
scanf("%d",&n1);
printf("Enter 2nd Number");
int n2;
scanf("%d",&n2);
int i,j;
for(j=n1;j<=n2;j++)
{
for(i=1;i<=10;i++)
{
printf("%d x %d = %d\n",j,i,j*i);
}
}
}
```
***OUTPUT***
```
Enter 1st Number8                                              
Enter 2nd Number9                                              
8 x 1 = 8                                                      
8 x 2 = 16                                                     
8 x 3 = 24                                                     
8 x 4 = 32                                                     
8 x 5 = 40                                                     
8 x 6 = 48                                                     
8 x 7 = 56                                                     
8 x 8 = 64                                                     
8 x 9 = 72                                                     
8 x 10 = 80                                                    
9 x 1 = 9                                                      
9 x 2 = 18                                                     
9 x 3 = 27                                                     
9 x 4 = 36                                                     
9 x 5 = 45                                                     
9 x 6 = 54                                                     
9 x 7 = 63                                                     
9 x 8 = 72                                                     
9 x 9 = 81                                                     
9 x 10 = 90
```
***Q10. Check whether the number is prime or composite.***
```C
#include <stdio.h>
int main() 
int n, i, flag = 0;
printf("Enter a positive integer: ");
scanf("%d", &n);
for (i = 2; i < n / 2; ++i)
if (n % i == 0)
flag = 1;
break;
}
}
if (n == 1) 
{
printf("1 is neither prime nor composite.");
}
else {
if (flag == 0)
printf("%d is a prime number.", n);
else
printf("%d is composite.", n);
}
return 0;
}
```
***OUTPUT***
```
Enter a positive integer: 29
29 is a prime number.
```
***Q11.Find the factorial of a number using recursion.***
```C
#include <stdio.h>
long int multiplyNumbers(int n); 
int main() 
{ 
int n; 
printf("Enter a positive integer: ");
scanf("%d", &n); 
printf("Factorial of %d = %ld", n, multiplyNumbers(n));
return 0; 
} 
long int multiplyNumbers(int n) 
{ if (n >= 1) 
return n*multiplyNumbers(n-1); 
else return 1;
}
```
***OUTPUT***
```
Enter a positive integer: 5                                                                                                   
Factorial of 5 = 120
```
***Q12.Takes two integers, operands and one operator from user, performs the operation and then print the result.***
```C
#include<stdio.h>
int main()
{
char o;
printf("Select an operator:");
scanf("%c",&o);
int a,b;
printf("Enter first number:");
scanf("%d",&a);
printf("Enter second nember:");
scanf("%d",&b);
switch(o)
{
case '+':
printf("Sum is %d",a+b);
break;

case '-':
printf("Difference is %d",a-b);
break;

case '*':
printf("Product is %d",a*b);
break;

case '/':
printf("Quotient is %d",a/b);                
break;
case '%':
printf("Remainder is %d",a%b);             
break;
default:
printf("Invalid Entry");
}
}
```
***OUTPUT***
```
Select an operator:*                                                                                                            
Enter first number:5                                                                                                            
Enter second nember:8                                                                                                           
Product is 40
```
***Q13.Program to reverse a number.***
```C
#include <stdio.h>
int main()
{
    int n, reversedNumber = 0, remainder;
    printf("Enter an integer: ");
    scanf("%d", &n);
    while(n != 0)
    {
    remainder = n%10;
    reversedNumber = reversedNumber*10 + remainder;
    n /= 10;
    }
    printf("Reversed Number = %d", reversedNumber);
    return 0;
}
```
***OUTPUT***
```
Enter an integer: 3111998                                                                                                     
Reversed Number = 8991113 
```
***Q14.Find the greatest number a the entered number.***
```C
#include <stdio.h>
int main() 
{
int i, n;
float arr[100];
printf("Enter the number of elements (1 to 100): ");
scanf("%d", &n);
for (i = 0; i < n; ++i)
printf("Enter number%d: ", i + 1);
scanf("%f", &arr[i]);
}
for (i = 1; i < n; ++i) 
{
if (arr[0] < arr[i])
arr[0] = arr[i];
}
printf("Largest element = %.2f", arr[0]);
return 0;
}
```
***OUTPUT***
```
Enter the number of elements (1 to 100): 5
Enter number1: 34.5
Enter number2: 2.4
Enter number3: -35.5
Enter number4: 38.7
Enter number5: 24.5
Largest element = 38.70
```
***Q15.Find the even numbers using array.***
```C
#include<stdio.h>
int main()
{
int a[10],i;
printf("\n\t\t\t\tFIND EVEN NUMBER USING ARRAY= ");
for(i=0;i<=9;i++)
{
   printf("\nENTER THE NUMBER %d=",i+1);
   scanf("%d",&a[i]);
}

printf("EVEN NUMBERS Are =");
for(i=0;i<=9;i++)
 {
if(a[i]%2==0)
{
printf("\n%d\n",a[i]);
}
}
}
```
***==++OUTPUT++==***
```
ENTER THE NUMBER 1=4                                                                                                            
                                                                                                                                
ENTER THE NUMBER 2=7                                                                                                            
                                                                                                                                
ENTER THE NUMBER 3=8                                                                                                            
                                                                                                                                
ENTER THE NUMBER 4=3                                                                                                            
                                                                                                                                
ENTER THE NUMBER 5=9                                                                                                            
                                                                                                                                
ENTER THE NUMBER 6=2                                                                                                            
                                                                                                                                
ENTER THE NUMBER 7=0                                                                                                            
                                                                                                                                
ENTER THE NUMBER 8=1                                                                                                            
                                                                                                                                
ENTER THE NUMBER 9=3                                                                                                            
                                                                                                                                
ENTER THE NUMBER 10=2                                                                                                           
EVEN NUMBERS Are =                                 
4                                                   
8                        
2                        
0  
2
```
***Q16.Program to check whether the number is positive or negative***
```C
#include <stdio.h>
int main() {
double num;
printf("Enter a number: ");
scanf("%lf", &num);
if (num <= 0.0) {
if (num == 0.0)
    printf("You entered 0.");
        else
            printf("You entered a negative number.");
}
else
printf("You entered a positive number.");
return 0;
}
```
***OUTPUT***
```
Enter a number: 9                                                                                                             
You entered a positive number
Enter a number: -4                                                                                                            
You entered a negative number.
```
***Q17.Simple calculator using switch and break statement.***
```C
#include <stdio.h>
int main() {
char operator;
double first, second;
printf("Enter an operator (+, -, *,): ");
scanf("%c", &operator);
printf("Enter two operands: ");
scanf("%lf %lf", &first, &second);
switch (operator) 
{
case '+':
printf("%.1lf + %.1lf = %.1lf", first, second, first + second);
break;
case '-':
printf("%.1lf - %.1lf = %.1lf", first, second, first - second);
break;
case '*':
printf("%.1lf * %.1lf = %.1lf", first, second, first * second);
break;
case '/':
printf("%.1lf / %.1lf = %.1lf", first, second, first / second);
break;
printf("Error! operator is not correct");
}
return 0;
}
```
***OUTPUT***
```
Enter an operator (+, -, *,): +                                                                                                 
Enter two operands: 2                                                                                                           
5                                                                                                                               
2.0 + 5.0 = 7.0
```
***Q18.Program to find total experience of employs.***
```C
#include<stdio.h>
void main()
{
 int n;
 printf("Enter the number of employees\n");
 scanf("%d",&n);
 int a[n];
 for(int i=1;i<=n;i++)
 { 
 printf("Enter e%d experience:", i);
 scanf("%d",&a[i]);
 }
 int sum=0;
 for (int j=1;j<=n;j++)
 {
  sum+=a[j];
 }
 printf("\n Total experience of employees is : %d\n", sum);
}
```
***OUTPUT***
```
Enter the number of employees                                                                                                   
6                                                                                                                               
Enter e1 experience:8                                                                                                           
Enter e2 experience:6                                                                                                           
Enter e3 experience:4                                                                                                           
Enter e4 experience:5                                                                                                           
Enter e5 experience:8                                                                                                           
Enter e6 experience:9                                                                                                           
                                                                                                                                
 Total experience of employees is : 40
```
***Q19.Program for matrix multiplication.***
```C
#include<stdio.h>
int main(){
int a[10][10],b[10][10],mul[10][10],r,c,i,j,k;
printf("enter the number of row=");
scanf("%d",&r);
printf("enter the number of column=");
scanf("%d",&c);
printf("enter the first matrix element=\n");
for(i=0;i<r;i++)
{
for(j=0;j<c;j++)
{
scanf("%d",&a[i][j]);
}
}
printf("enter the second matrix element=\n");
for(i=0;i<r;i++)
{
for(j=0;j<c;j++)
{
scanf("%d",&b[i][j]);
}
}

printf("multiply of the matrix=\n");
for(i=0;i<r;i++)
{
for(j=0;j<c;j++)
{
mul[i][j]=0;
for(k=0;k<c;k++)
{
mul[i][j]+=a[i][k]*b[k][j];
}
}
}
for(i=0;i<r;i++)
{
for(j=0;j<c;j++)
{
printf("%d\t",mul[i][j]);
}
printf("\n");
}
return 0;
}
```
***OUTPUT***
```
enter the number of row=3                                                                                                       
enter the number of column=2                                                                                                    
enter the first matrix element=                                                                                                 
3                                                                                                                               
9                                                                                                                               
7                                                                                                                               
4                                                                                                                               
7                                                                                                                               
9                                                                                                                               
enter the second matrix element=                                                                                                
4                                                                                                                               
7                                                                                                                               
8                                                                                                                               
6                                                                                                                               
5                                                                                                                               
3                                                                                                                               
multiply of the matrix=                                                                                                         
84      75                                                                                                                      
60      73                                                                                                                      
100     103 
```
***Q20.Print inverted half pyramid using * and numbers.***
```C
#include<stdio.h>
int main() {
int i, j, rows;
printf("Enter number of rows: ");
scanf("%d", &rows);
for (i=rows; i>=1; --i) 
{
for (j=1; j<=i; ++j)
{
printf("* "); 
}
printf("\n");
}   
return 0;
}
```
***OUTPUT***
```
Enter number of rows: 8                                                                                                         
* * * * * * * *                                                                                                                 
* * * * * * *                                                                                                                   
* * * * * *                                                                                                                     
* * * * *                                                                                                                       
* * * *                                                                                                                         
* * *                                                                                                                           
* *                                                                                                                             
* 
```
