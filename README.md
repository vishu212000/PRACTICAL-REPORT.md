# PRACTICAL-REPORT.md

PROGRAMMING FOR PROBLEM SOLVING ESC-18105

## NAME-*VISHWAJIT SINGH*

## ROLL NO-*1916085*

## BRANCH-*ELECTRICAL ENGINEERING*

## SECTION-*EE(B)*

# PROGRAM No 1:-PROGRAM TO PRINT WELCOME MESSAGE
~~~C
  #include <stdio.h>  
  int main()
  {
      puts("Welcome To Budding Engineers");
  }
~~~
OUTPUT
~~~
Welcome To Budding Engineers 
~~~
# PROGRAM No 2:-PROGRAM TO PRINT THE ADDRESS
~~~C
#include <stdio.h>  
int main()  
{
    puts("H.no-16\nVILL-DHAL, TEHSIL-MUKERIAN\nDISTT PATHANKOT\nPUNJAB");  
}
~~~
OUTPUT
~~~
 H.no-16
 VILL-DHAL, TEHSIL-MUKREAIAN
DISTT-PATHANKOT
PUNJAB
~~~
# PROGRAM No 3:-PROGRAM TO FIND THE SUM OF TWO NUMBERS
~~~C
#include <stdio.h>
int main()
{
        int a,b,c;  
        printf("enter the numbers"); 
        scanf("%d %d",&a,&b);                            
        c=a+b;
        printf("sum of numbers is %d\n",c);  
        return 0;  
}
~~~
OUTPUT
~~~
 enter the numbers 13
 12
 sum of numbers is 25
~~~
# PROGRAM No 4:-PROGRAM TO CONVERT TEMPERATURE FROM CELCIUS TO FAHRENHIET
~~~C
#include <stdio.h>
void main()
{
float f,c;
printf("enter temperature ");
scanf("%f",&f);
c=((f-32)*5)/9;
printf("temp in celcius is %.2f\n",c);
}
~~~
OUTPUT
~~~
enter temperature 97
temp in celcius is 36.11
~~~
# PROGRAM No 5:-PROGRAM TO FIND AREA AND PERIMETER OF A CIRCLE
~~~C
#include <stdio.h>
void main()
{
float diameter, perimeter, area;
printf("enter diameter");
scanf("%f", &diameter);
perimeter = 22/7 * diameter;
area = perimeter * diameter / 4.0;
printf("\n\nDia: %.2f\nPerimeter: %.2f\nArea: %.2f\n\n",diameter, perimeter, area);
}
~~~
OUTPUT
~~~
enter diameter 14
Dia: 14.00
Perimeter: 42.00
Area: 147.00
~~~
# PROGRAM No 6:-PROGRAM TO REVERSE TWO DIGIT NUMBER WITHOUT USING 3RD VARIABLE
~~~C
#include <stdio.h>
void main()
{
  int a,b;
  printf(" enter number");
  scanf("%d",&a);
  b=a;
  a=a%10;
  b=b/10;
  b=a*10+b;
  printf("reverse no is %d",b);
  }
  ~~~
OUTPUT
~~~
enter number 41  
reverse no is 14
~~~
# PROGRAM No 7:-PROGRAM TO CHECK WHETHER THE NUMBER IS EVEN OR ODD
~~~C
#include <stdio.h>
void main()
{
        int a;
        printf("enter number: ");
        scanf("%d",&a);
        if (a%2==0)
        printf("%d is even",a);
        else
        printf("%d is odd",a);
}
~~~
OUTPUT
~~~
enter number: 12
12 is even
~~~
# PROGRAM No 8:-PROGRAM TO FIND FACTORIAL OF A NUMBER
~~~c
#include <stdio.h>
void main()
{
        int a,n=1,i;
        printf("Enter a no");
        scanf("%d",&i);
        for(a=1;a<=i;a++)
        n=n*a;
        printf("factorial of a is %d \n",n);
}
~~~
OUTPUT
~~~
Enter a no 6
factorial of a is 720   
~~~
# PROGRAM No 9:-PROGRAM TO REVERSE A NUMBER
~~~c
#include <stdio.h>
void main()
{
        int a,n,r=0;
        printf("enter number");
        scanf("%d",&n);
        while(n>0)
        {
                a=n%10;
                r=r*10+a;
                n=n/10;
        }
        printf("reverse no is %d \n",r);
}
~~~
OUTPUT
~~~
enter number 461 
reverse no is 164
~~~
# PROGRAM No 10:-PROGRAM TO PRINT FIZZBUZZ
~~~C
#include <stdio.h>
int main()
{
        int a,i;
        printf("enter number ");
        scanf("%d",&a);
        for(i=1;i<=a;i++)
        {
                if(i%15==0)
                printf("fizzbuzz\n");
                else if(i%5==0)
                printf("buzz\n");
                else if(i%3==0)
                printf("fizz\n");
                else
                printf("%d\n",i);
        }
        return 0;
}
~~~
OUTPUT
~~~
enter number 30
1
2
fizz
4
buzz
fizz
7
8
fizz
buzz
11
fizz
13
14
fizzbuzz
16
17
fizz
19
buzz
fizz
22
23
fizz
buzz
26
fizz
28
29
fizzbuzz
~~~
# PROGRAM No 11:-PROGRAM TO PRINT DAYS OF A WEEK
~~~C
#include <stdio.h>
void main()
{
        char ch;
        printf("enter s for sunday\n m for monday\n t for tuesday\n w for wednesday\n h for thursday\n f for friday\n a for saturday\n");
        scanf(" %s",&ch);
        switch (ch)
        {
                case 's':
                printf("sunday");
                break;
                case 'm':
                printf("monday");
                break;
                case 't':
                printf("tuesday");
                break;
                case 'w':
                printf("wednesday");
                break;
                case 'h':
                printf("thrusday");
                break;
                case 'f':
                printf("friday");
                break;
                case 'a':
                printf("saturday");
                break;
                default :
                printf("wrong input");
                break;
                case 'w':
                printf("wednesday");
                break;
                case 'h':
                printf("thrusday");
                break;
                case 'f':
                printf("friday");
                break;
                case 'a':
                printf("saturday");
                break;
                default :
                printf("wrong input");
                break;
        }
}
~~~
OUTPUT
~~~
enter s for sunday
      m for monday
      t for tuesday
      w for wednesday
      h for thursday
      f for friday
      a for saturday
      h for thursday
~~~
# PROGRAM No 12:-PROGRAM TO MAKE A CALCULATOR
~~~C
#include <stdio.h>
int main()
{
        int a,b,c;
        char cal;
        printf("enter a and b operator=");
        scanf("%d %d %c",&a,&b,&cal);
        switch (cal)
        {
                case '+':
                c=a+b;
                printf("%d",c);
                break;
                case '-':
                c=a-b;
                printf("%d",c);
                break;
                case '*':
                c=a*b;
                printf("%d",c);
                break;
                case '/':
                c=a/b;
                printf("%d",c);
        }
        printf("\n");
}
~~~
OUTPUT
~~~
enter a and b operator= 12  
15    
27
~~~
# PROGRAM No 13:-PROGRAM TO CHECK WHETHER A YEAR IS LEAP YEAR OR NOT
~~~C
#include <stdio.h>
int main()
{
        int year;
        printf("Enter a year ");
        scanf("%d",&year);
        if (year%4==0)
        printf("%d is a leap year\n",year);
        else
        printf("%d is not a leap year\n",year);
        return 0;
}
~~~
OUTPUT
~~~
enter a year 2016
2016 is a leap year
~~~
# PROGRAM No 14:-PROGRAM TO CHECK WHETHER A NUMBER IS PRIME OR NOT
~~~C
#include <stdio.h>
void main()
{
int x=0,i,n;
printf("enter number ");
scanf("%d",&i);
for(n=1;n<=i;n++)
{
if(i%n==0)
x++;
}
if(x==2)
{
printf("no is prime\n");
}
else
{
printf("no is not prime\n");
}
}
OUTPUT

enter number 11
no is prime
~~~
# PROGRAM No 15:-PROGRAM TO CHEACK WHETHER A NUMBER IS PALLINDROME OR NOT
~~~C
#include <stdio.h>
void main()
{
        int i,a,n,r=0;
        printf("enter number");
        scanf("%d",&n);
        i=n;
        while(n>0)
        {
                a=n%10;
                r=r*10+a;
                n=n/10;
        }
        printf("Reverse no is %d \n",r);
        if(i==r)
        printf("no is pallindrome");
        else
        printf("no is not pallindrome");
}
~~~
OUTPUT
~~~
enter number 121
Reverse no is 121
no is pallindrome
~~~
# PROGRAM No 16:-PROGRAM TO PRINT FIBONACCI SERIES
~~~C
#include <stdio.h>
int main()
{
        int a=1,b=1,s,i;
        printf("Enter value of i");
        scanf("%d",&i);
        printf(" %d %d ",a,b);
        for(a=1;a<=i;)
        {
                s=a+b;
                printf("%d ",s);
                b=a;
                a=s;
        }
        return 0;
}
~~~
OUTPUT
~~~
Enter value of i 20
1 1 2 3 5 8 13 21
~~~
# PROGRAM No 17:-PROGRAM TO ENTER AND PRINT 10 ELEMENTS USING 1-D ARRAY
~~~C
#include <stdio.h>
int main()
{
        char name[10];
        int marks;
        int i;
        for (i=0;i<10;i++)
        {
                printf("enter name ");
                scanf("%s",&name);
                printf("enter marks ");
                scanf("%d",&marks);
        }
}
~~~
OUTPUT
~~~
enter name a 
enter marks 1
enter name b
enter marks 2
enter name c
enter marks 3
enter name d
enter marks 4
enter name e
enter marks 5
enter name f
enter marks 6
enter name g
enter marks 7
enter name h
enter marks 8
enter name i
enter marks 9
enter name j
enter marks 10
~~~
# PROGRAM No 18:-PROGRAM TO PRINT A TWO MATRIX
~~~C
#include<stdio.h>
int main()
{
int a[3][3],b[3][3],i,j;
printf("Enter matrix a");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d",&a[i][j]);
}
printf("Enter matrix b");
for (i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d",&b[i][j]);
}
printf("Matrix a\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d ",a[i][j]);
printf("\n");
}
printf("\n");
printf("Matrix b\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d ",b[i][j]);
printf("\n");
}
printf("\n");
return 0;
}
~~~
OUTPUT
~~~
  Enter matrix a
1
2
3
4
5
6
7
8
9
Enter matrix b
1
2
3
4
5
6
7
8
9
Matrix a
1 2 3 
4 5 6 
7 8 9 

Matrix b
1 2 3 
4 5 6 
7 8 9
~~~
# PROGRAM No 19:-PROGRAM TO ADD TWO MATRIX
~~~C
#include <stdio.h>
int main()                                                                
{
int a[3][3],b[3][3],c[3][3],i,j;
printf("enter matrix a\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d",&a[i][j]);
}
printf("enter matrix b\n");
for (i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d",&b[i][j]);
}
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
c[i][j]=a[i][j]+b[i][j];
}
printf("\n");
printf("sum of matrix\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d ",c[i][j]);
printf("\n");
}
printf("\n");
}
~~~
OUTPUT
~~~
enter matrix a
1
2
3
4
5
6
7
8
9
enter matrix b
1
2
3
4
5
6
7
8
9

sum of matrix
2 4 6 
8 10 12 
14 16 18 
~~~
# PROGRAM No 20:-PROGRAM TO TRANSPOSE A MATRIX
~~~C
#include <stdio.h>
int main()
{
int a[3][3],b[3][3],c[3][3],i,j;
printf("enter matrix a\n");
for(i=0;i<=2;i++)                                                         
{
for(j=0;j<=2;j++)
scanf("%d",&a[i][j]);
}
printf("matrix a\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d ",a[i][j]);
printf("\n");
}
for (i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
b[j][i]=a[i][j];
}
printf("\n");
printf("transpose of matrix\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d ",b[i][j]);
printf("\n");
}
printf("\n");
return 0;
}
~~~
OUTPUT
~~~
enter matrix a
1
2
3
4
5
6
7
8
9
matrix a
1 2 3 
4 5 6 
7 8 9 

transpose of matrix
1 4 7 
2 5 8 
3 6 9
~~~
# PROGRAM No 21:-PROGRAM TO SUBTRACT TWO MATRIX
~~~C
#include <stdio.h>
int main()
{
int a[3][3],b[3][3],c[3][3],i,j;
printf("enter matrix a\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d",&a[i][j]);
}
printf("enter matrix b\n");
for (i=0;i<=2;i++)                                                        
{
for(j=0;j<=2;j++)
scanf("%d",&b[i][j]);
}
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
c[i][j]=a[i][j]-b[i][j];
}
printf("\n");
printf("subtraction of matrix\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf("%d ",c[i][j]);
printf("\n");
}
printf("\n");
return 0;
}
~~~
OUTPUT
~~~
enter matrix a
1
0
0
0
1
0
0
0
1
enter matrix b
1
0
0
0
1
0 
0
0
1

subtraction of matrix
0 0 0 
0 0 0 
0 0 0
~~~
# PROGRAM No 22:- PROGRAM TO MULTIPLY TWO MATRIX
~~~C
#include <stdio.h>
int main()
{
int a[3][3],b[3][3],c[3][3],i,j,k,sum=0;
printf("enter matrix a\n");
for(i=0;i<=2;i++)                                        
{
for(j=0;j<=2;j++)
scanf("%d",&a[i][j]);
}
printf("enter matrix b\n");
for (i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
scanf("%d",&b[i][j]);
}
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
{
for(k=0;k<=2;k++)
{
sum=sum+a[i][k]*b[k][j];
}
printf("\n");
c[i][j]=sum;
sum=0;
}
}
printf("multiplicationof matrix\n");
for(i=0;i<=2;i++)
{
for(j=0;j<=2;j++)
printf(" %d ",c[i][j]);
printf("\n");
}
printf("\n");
}
~~~
OUTPUT
~~~
enter matrix a
1
2
3
4
5
6
7
8
9
enter matrix b
1
2
3
4
5
6
7
8
9
multiplicationof matrix
 30  36  42 
 66  81  96 
 102  126  150 
 ~~~
# PROGRAM No 23:-PROGRAM TO SQUARE A NUMBER USING FUNCTIONS
~~~C
#include <stdio.h>
int square(int );
void main()
{
       int a,res;
       printf("enter number ");
       scanf("%d",&a);
       res=square(a);
       printf("square is %d\n",res);
}
int square(int a)
{
       int res;
       res=a*a;
       return res;
}
OUTPUT

enter number 14
square is 196
~~~
# PROGRAM No 24:-PROGRAM TO SWAP A NUMBER BY CALLING FUNCTION BY VALUE
~~~C
#include <stdio.h>
int swap(int num1,int num2);
void main()
{       
        int a,b,c;
        printf("enter the numbers a and b ");
        scanf("%d %d",&a,&b);
        printf("numbers before swap are %d and %d\n",a,b);
        c=swap(a,b);
        printf(" numbers after swap are %d and %d\n",a,b);
}
int swap(int num1,int num2)
{
        int c;
        c=num1;
        num1=num2;
        num2=c;
}
OUTPUT

enter the numbers a and b 12
13
numbers before swap are 12 and 13
numbers after swap are 12 and 13
~~~
# PROGRAM No 25:-PROGRAM TO SWAP TWO NUMBERS BY CALLING FUNCTION BY REFRENCE
~~~C
#include <stdio.h>
int swap(int *num1,int *num2);
void main()
{      
        int a,b,c;
        printf("enter the numbers a and b ");
        scanf("%d %d",&a,&b);
        printf("numbers before swap are %d and %d\n",a,b);
        c=swap(&a,&b);
        printf(" numbers after swap are %d and %d\n",a,b);
}
int swap(int *num1,int *num2)
{
        int c;
        c=*num1;
        *num1=*num2;
        *num2=c;
}
~~~
OUTPUT
~~~
enter the numbers a and b 12
13
numbers before swap are 12 and 13
numbers after swap are 13 and 12
~~~
# PROGRAM No 26:-PROGRAM TO FIND FACTORIAL USINF RECURSION
~~~C
#include <stdio.h>
int factorial(int);
int main()
{
        int n,f;
        printf("enter the number ");
        scanf("%d",&n);
        if(n<0)
        printf("factorial is not defined");
        else
        {
                f=factorial(n);
                printf("factorial of number is %d\n",f);
        }
return 0;
}                                                                         
int factorial(int n)
{
        if(n==1)
        return 1;
        else                                                              
        return (n*factorial(n-1));
}
~~~
OUTPUT
~~~
enter the number 5
factorial of number is 120
~~~
# PROGRAM No 27:-PROGRAM TO PRINT FIBBONACCI SERIES USING RECURSSION
~~~C
#include <stdio.h>
int fibbo(int num1);
void main()
{       
        int n,c,i=0;
        printf("enter the number ");
        scanf("%d",&n);
        for (c=1;c<=n;c++)
        {
                printf(" %d ",fibbo(i));
                i++;                                                      
        }
        printf("\n");
}       
int fibbo(int n)
{       
        if (n==0 || n==1)
        return n;
        else
        return (fibbo(n-1)+fibbo(n-2));
}
~~~
OUTPUT
~~~
enter the number 8
 0  1  1  2  3  5  8  13 
~~~
# PROGRAM No 28:-PROGRAM TO DISPLAY A STUCTURE
~~~C
#include <stdio.h>
struct xyz
{       
char name[5];
int marks;      
};              
int main()
{       
struct xyz p;
for(int i=0;i<=4;i++)
{
printf("enter name ");
scanf("%s",p.name);
printf("\n enter marks");
scanf("%d",&p.marks);
}
return 0;
}
~~~
OUTPUT
~~~
enter name a
 enter marks 1
enter name b
 enter marks 2
enter name c
 enter marks 3
enter name d
 enter marks 4
enter name e
 enter marks 5
~~~
# PROGRAM No 29:-PROGRAM TO DISPLAY ADDRESS OF A VARIABLE USING POINTERS
~~~C
#include <stdio.h>
void main()
{
        int n,*p;
        p=&n;
        n=100;
        printf("using variable n:\n");
        printf("value of n:%d\n address of n %u\n",n,&n);
        printf("using pointer n: \n");
        printf("value of n:%d\n address of n %u\n",*p,p);
}
~~~
OUTPUT
~~~
using variable n:
value of n:100
 address of n 804324724
using pointer n: 
value of n:100
 address of n 804324724
~~~
# PROGRAM No 30:-PROGRAM TO PRINT ADDRESS OF A VARIABLE USING POINTERS
~~~C
#include <stdio.h>
void main()
{                                                                                       
       int a[10],*p,i;
       p=&a[0];
       printf("enter the elements of array\n");
       for(i=0;i<=9;i++)
       {
               printf("enter elements %02d:",i+1);
               scanf("%d",p+i);
       }
       printf("entered elements are:\n");
       printf("address:\t \t value\n");
       for (i=0;i<=9;i++)
       printf("%08x\t %03d\n",(p+i),*(p+i));
}
~~~
OUTPUT
~~~
enter the elements of array
enter elements 01:12
enter elements 02:13
enter elements 03:1615
enter elements 04:16
enter elements 05:19 
enter elements 06:18
enter elements 07:14
enter elements 08:12
enter elements 09:17
enter elements 10:16
entered elements are:
address:         value
85c17510         012
85c17514         013
85c17518         1615
85c1751c         016
85c17520         019
85c17524         018
85c17528         014
85c1752c         012
85c17530         017
85c17534         016
~~~
