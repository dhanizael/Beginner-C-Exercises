# Question 1

### **Question:**

> ***Write a program to print Hello World!.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
printf("Hello,world!");
return 0;
}
```
----------------------------------------


# Question 2

### **Question:**

> ***Write a program to find the area of a circle.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int r, area;
r = 2;
area = 3.14 * r * r;
printf("The area of the circle = %d", area);
return 0;
}
```
----------------------------------------

# Question 3

### **Question:**

> ***Write a program to find the sum of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int a, b, sum;
a=1;
b=2;
sum = a + b;
printf("The sum of a and b = %d", sum);
return 0;
}
```
----------------------------------------

# Question 4

### **Question:**

> ***Write a program to find the square of a number.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
#include<math.h>
int main()
{
int a, b;
a=2;
b = pow((a), 2);
printf("The square of a = %d", b);
return 0;
}
```
----------------------------------------

# Question 5

### **Question:**

> ***Write a program to find the greatest of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int a, b;
a = 2;
b = 3;
if(a>b)
{
printf("a is greater than b");
}
else
{
printf("b is greater than a");
}
return 0;
}
```
----------------------------------------

# Question 6

### **Question:**

> ***Write a program to print the average of the elements in the array.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i, avg, sum = 0;
int num [5] = {16, 18, 20, 25, 36};
for(i=0; i<5; i++)
sum = sum + num [i];
avg = sum/5;
printf("Sum of the Elements in the array = %d", sum);
printf("Average of the elements in the array= %d", avg);
return 0;
}
```
----------------------------------------

# Question 7

### **Question:**

> ***Write a program such that a Switch (case) allows to make a decision from the number of choices, i.e., from the number of cases.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
char ch;
printf("Enter any character:");
scanf("%c", &ch);
switch(ch)
{
case 'R':
printf("Red");
break;
case 'W':
printf("White");
break;
case 'Y':
printf("Yellow");
break;
case 'G':
printf("Green");
break;
default:
printf("Error");
break;
}
return 0;
} 
```
----------------------------------------

# Question 8

### **Question:**

> ***Write a program to find the greatest of two numbers using pointers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int x, y, *p, *q;
printf("Enter any integer:");
scanf("%d", &x);
printf("Enter any integer:");
scanf("%d", &y);
p = &x;
q = &y;
if(*p>*q)
{
printf("x is greater than y");
}
if(*q>*p)
{
printf("y is greater than x");
}
return 0;
}
```
----------------------------------------

# Question 9

### **Question:**

> ***Write a program to print the address of x and the value assigned to x.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main()
{
int x, *p;
x = 1;
p = &x;
printf("The address of the variable x =%d", p);
printf("The value of the variable x =%d", *p);
return 0;
} 
```
----------------------------------------

# Question 10

### **Question:**

> ***Write a program to print the first 10 numbers starting from one together with their squares and cubes.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i;
for( i=1; i<=10; i++)
printf("Number=%d its square=%d its cube=%d\n", i , i*i, i*i*i);
return 0;
} 
```
----------------------------------------

# Question 11

### **Question:**

> ***Write a program:</br>
If you enter a character M</br>
Output must be: ch = M.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
char M;
printf("Enter any character:");
scanf("%c", &M);
printf("ch=%c", M);
return 0;
} 
```
----------------------------------------

# Question 12

### **Question:**

> ***Write a program to print the multiplication table of a number.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int n, i;
printf("Enter any number:");
scanf("%d", &n);
for( i=1; i<=5; i++)
printf("%d * %d = %d\n", n, i, n*i);
return 0;
}
```
----------------------------------------


# Question 13

### **Question:**

> ***Write a program to print the product of the first 10 digits.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i, product = 1;
for( i=1; i<=10; i++)
product = product * i;
printf("The product of the first 10 digits =%d", product);
return 0;
}
```
----------------------------------------

# Question 14

### **Question:**

> ***Write a program to print whether the given number is positive or negative.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int a;
a = -35;
if(a>0)
{
printf("Number is positive");
}
else
{
printf("Number entered is negative");
}
return 0;
}
```
----------------------------------------

# Question 15

### **Question:**

> ***Write a program to check the equivalence of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int x, y;
printf("Enter any number:");
scanf ("%d", &x);
printf("Enter any number:");
scanf ("%d", &y);
if(x-y==0)
{
printf("The two numbers are equivalent");
}
else
{
printf("The two numbers are not equivalent");
}
return 0;
}
```
----------------------------------------

# Question 16

### **Question:**

> ***Write a program to print the remainder of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int a, b, c;
printf("Enter any number:");
scanf("%d", &a);
printf("Enter any number:");
scanf("%d", &b);
c = a%b;
printf("The remainder of a and b = %d", c);
return 0;
}
```
----------------------------------------

# Question 17

### **Question:**

> ***Write a program to print the given number is even or odd.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int a;
printf("Enter any number:");
scanf ("%d", &a);
if(a%2 = = 0)
{
printf("The number is even");
}
else
{
printf("The number is odd");
}
return 0;
}
```
----------------------------------------

# Question 18

### **Question:**

> ***Write a program to print the characters from A to Z.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
char a;
for( a='A'; a<='Z'; a++)
printf("%c\n", a);
return 0;
}
```
----------------------------------------

# Question 19

### **Question:**

> ***Write a program to find the incremented and decremented values of two numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int a, b, c, d, e, f;
a = 10;
b=12;
c=a+1;
d=b+1;
e=a-1;
f=b-1;
printf("The incremented value of a =%d", c);
printf("The incremented value of b =%d", d);
printf("The decremented value of a =%d", e);
printf("The decremented value of b =%d", f);
return 0;
}
```
----------------------------------------

# Question 20

### **Question:**

> ***Write a program to calculate the simple interest.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int P,T, R, SI;
P = 1000;
T = 2;
R = 3;
SI = P*T*R/100;
printf("The simple interest = %d", SI);
return 0;
}
```
----------------------------------------

# Question 21

### **Question:**

> ***Write a program to Find the largest of three numbers.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int a, b, c;
printf("Enter any number:");
scanf("%d", &a);
printf("Enter any number:");
scanf("%d", &b);
printf("Enter any number:");
scanf("%d", &c);
if(a>b&&a>c)
{
printf("%d is greater than %d and %d", a, b, c);
}
else if (b>a&&b>c)
{
printf("%d is greater than %d and %d", b, a, c);
}
else
{
printf("%d is greater than %d and %d", c, b, a);
}
return 0;
}
```
----------------------------------------

# Question 22

### **Question:**

> ***Write a program to print the factorial of the entered number.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i, n, fact=1 ;
printf("Enter any number:");
scanf("%d", &n);
for(i=1; i<=n; i++)
fact = fact *i;
printf("\n Entered number is: %d", n);
printf("\n The factorial of the entered number %d is: %d", n, fact);
return 0;
}
```
----------------------------------------

# Question 23

### **Question:**

> ***Write a program to print the length of the entered string.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
#include<string.h>
int main()
{
char ch[4];
printf("Enter any word: ");
scanf("%c", &ch);
printf("The length of the string = %d", strlen(ch));
return 0;
}
```
----------------------------------------

# Question 24

### **Question:**

> ***Write a program to print the ASCII value of the entered character.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
char ch ='A';
printf("The ASCII value of ch is: %d", ch);
return 0;
}
```
----------------------------------------


# Question 25

### **Question:**

> ***Write a program to check whether the entered character is a lower case letter or not.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
char ch = 'a';
if(islower(ch))
printf("you have entered the lower case letter");
else
printf("you have entered the upper case letter");
return 0;
}
```
----------------------------------------


# Question 26

### **Question:**

> ***Write a program to check whether the entered character is a upper case letter or not.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
char ch = 'a';
if(isupper(ch))
printf("you have entered the upper case letter");
else
printf("you have entered the lower case letter");
return 0;
}
```
----------------------------------------

# Question 27

### **Question:**

> ***Write a program to convert the lower case letter to upper case letter.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
char ch = 'a';
char b = toupper(ch);
printf("lower case letter %c is converted to upper case letter %c", ch, b);
return 0;
}
```
----------------------------------------

# Question 28

### **Question:**

> ***Write a program to print the output:</br>
Einstein [0] = E</br>
Einstein [1] = I</br>
Einstein [2] = N</br>
Einstein [3] = S</br>
Einstein [4] = T</br>
Einstein [5] = E</br>
Einstein [6] = I</br>
Einstein [7] = N</br>***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i;
char name [8] = {' E' , ' I', ' N', ' S', ' T ', ' E', ' I', ' N'};
for(i=0; i<8; i++)
printf("\n Element [%d] = %c", i, name[i]);
return 0;
}
```
----------------------------------------

# Question 29

### **Question:**

> ***Write a program to print the output:</br>
Name of the book = B</br>
Price of the book = 135.00</br>
Number of pages = 300</br>
Edition = 8</br>
using structures.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
struct book {
char name;
float price;
int pages;
int edition;
};
struct book b1;
b1.name = 'B';
b1.price = 135.00;
b1.pages = 300;
b1.edition = 8;
printf("\n Name of the book = %c", b1.name);
printf("\n Price of the book = %f", b1.price);
printf("\n Number of pages = %d", b1.pages);
printf("\n Edition of the book = %d", b1.edition);
return 0;
}
```
----------------------------------------

# Question 30

### **Question:**

> ***Write a program to find square of a number using functions.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int square();
int main()
{
int answer;
answer = square();
printf("Square of the given number=%d", answer);
return(0);
}
int square()
{
int x;
printf("Enter any integer:");
scanf("%d", &x);
return x*x;
}
```
----------------------------------------

# Question 31

### **Question:**

> ***Write a program To print "hello world" 10 times.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i;
for (i =1; i<=10; i ++)
printf("hello world \n");
return 0;
}
```
----------------------------------------


# Question 32

### **Question:**

> ***Write a program to print first 5 numbers using do while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i =1;
do
{
printf("%d\n", i++);
} while (i<=5);
return 0;
}
```
----------------------------------------

# Question 33

### **Question:**

> ***Write a program to print the output:</br>
body [b] = b</br>
body [o] = o</br>
body [d] = d</br>
body [y] = y</br>***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main()
{
char i;
char body [4] = {'b', 'o', 'd', 'y'};
for(i=0; i<4; i++)
printf("\n body[%c] = %c", body[i] , body[i]);
return 0;
}
```
----------------------------------------


# Question 34

### **Question:**

> ***What will be the output of the below program:***

---------------------------------------

```C language
#include<stdio.h>
#include<stdlib.h>
int main () {
printf("linux\n");
exit (0);
printf("php\n");
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
linux
```
----------------------------------------

# Question 35

### **Question:**

> ***Write a program to check whether a character is an alphabet or not.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
#include <ctype.h>
int main()
{
int a =2;
if(isalpha(a))
{
printf("The character a is an alphabet");
}
else
{
printf("The character a is not an alphabet");
}
return 0;
}
```
----------------------------------------

# Question 36

### **Question:**

> ***Write a program to calculate the discounted price and the total price after discount</br>
Given:</br>
If purchase value is greater than 1000, 10% discount</br>
If purchase value is greater than 5000, 20% discount</br>
If purchase value is greater than 10000, 30% discount.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
double PV;
printf("Enter purchased value:");
scanf("%lf", &PV);
if(PV>1000)
{
printf("\n Discount=%lf", PV* 0.1);
printf("\n Total=%lf", PV - PV* 0.1);
}
else if(PV>5000)
{
printf("\n Discount =%lf", PV* 0.2);
printf("\n Total=%lf", PV - PV* 0.1);
}
else
{
printf("\n Discount=%lf", PV* 0.3);
printf("\n Total=%lf", PV - PV* 0.1);
}
return 0;
}
```
----------------------------------------

# Question 37

### **Question:**

> ***Write a program to print the first ten natural numbers using while loop statement.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int i = 1;
while (i<=10)
{
printf("%d\n", i++);
}
return 0;
}
```
----------------------------------------

# Question 38

### **Question:**

> ***What will be the output of the below program:***

---------------------------------------

```C language
#include <stdio.h>
int main()
{
int i;
for (i=1; i<=5; i++)
{
if (i==3)
{
continue;
}
printf("%d\n ", i);
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
1
2
4
5
```
----------------------------------------

# Question 39

### **Question:**

> ***Write a program to find the size of an array.***

----------------------------------------

<strong>Solution: </strong>

```C language
#include <stdio.h>
int main()
{
   int num [] = {11, 22, 33, 44, 55, 66};
    int n;

    /* Calculating the size of the array with this formula.
     * n = sizeof(array_name) / sizeof(array_name[0])
     * This is a universal formula to find number of elements in
     * an array, which means it will work for arrays of all data
     * types such as int, char, float etc.
     */
    n = sizeof(num) / sizeof(num [0]);
    printf("Size of the array is: %d\n", n);
    return 0;
}
```
----------------------------------------

# Question 40

### **Question:**

> ***What would be the output of the following programs:***

----------------------------------------

```C language
#include <stdio.h>
int main()
{
int i;
for (i=1; i<=5; i++)
{
if (i==3)
{
break;
}
printf("%d\n", i);
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
1
2
```
----------------------------------------

```C language
#include <stdio.h>
int main()
{
int i;
for(i=1;i<=5;i++)
{
if(i==3)
{
goto HAI;
}
printf("\n %d ",i);
}
HAI : printf("\n Linux");
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
1
2
Linux
```
----------------------------------------

```C language
#include<stdio.h>
int main()
{
int i = 54;
int y = i<<1;
printf("The value of y = %d", y);
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
The value of y = 108
```
----------------------------------------

```C language
#include<stdio.h>
int main()
{
int i = 54;
int y = i>>1;
printf("The value of y = %d", y);
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
The value of y = 27
```
----------------------------------------

```C language
#include<stdio.h>
#include <stdlib.h>
int main()
{
int a, b;
a= - 2;
b= abs(a);
printf("Absolute value = %d", b);
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
Absolute value = 2
 ```
----------------------------------------

```C language
#include <stdio.h>
int main()
{
for( ; ; ) 
{
printf("This loop will run forever.\n");
}
return 0;
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever.
This loop will run forever. ......... 
```
----------------------------------------


```C language
#include<stdio.h>
int main()
{
printf("Hello,world!");
return 0;
printf("Hello,world!");
}
```
----------------------------------------

<strong>Solution: </strong>

```C language
Hello,world! 
```
----------------------------------------

# Question 41

### **Question:**

> ***Write a program to check whether the person is a senior citizen or not.***

---------------------------------------

<strong>Solution: </strong>

```C language
#include<stdio.h>
int main()
{
int age;
printf("Enter age:");
scanf("%d", &age);
if(age>=60)
{
printf("senior citizen");
}
else
{
printf("not a senior citizen");
}
return 0;
}
```
----------------------------------------

# Question 42

### **Question:**

> ***Write a program to Display Fibonacci Sequence.***

---------------------------------------

<strong>Solution: </strong>

```c

#include <stdio.h>
int main() {
    int i, n, t1 = 0, t2 = 1, nextTerm;
    printf("Enter the number of terms: ");
    scanf("%d", &n);
    printf("Fibonacci Series: ");

    for (i = 1; i <= n; ++i) {
        printf("%d, ", t1);
        nextTerm = t1 + t2;
        t1 = t2;
        t2 = nextTerm;
    }

    return 0;
}
```
----------------------------------------

# Question 43

### **Question:**

> ***Write a program to Find GCD of two Numbers.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
int main()
{
    int n1, n2, i, gcd;

    printf("Enter two integers: ");
    scanf("%d %d", &n1, &n2);

    for(i=1; i <= n1 && i <= n2; ++i)
    {
        // Checks if i is factor of both integers
        if(n1%i==0 && n2%i==0)
            gcd = i;
    }

    printf("G.C.D of %d and %d is %d", n1, n2, gcd);

    return 0;
}
```
----------------------------------------

# Question 44

### **Question:**

> ***Write a program to Find LCM of two Numbers.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
int main() {
    int n1, n2, max;
    printf("Enter two positive integers: ");
    scanf("%d %d", &n1, &n2);

    // maximum number between n1 and n2 is stored in min
    max = (n1 > n2) ? n1 : n2;

    while (1) {
        if (max % n1 == 0 && max % n2 == 0) {
            printf("The LCM of %d and %d is %d.", n1, n2, max);
            break;
        }
        ++max;
    }
    return 0;
}
```
----------------------------------------


# Question 45

### **Question:**

> ***Write a program to Reverse a Sentence Using Recursion.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
void reverseSentence();
int main() {
    printf("Enter a sentence: ");
    reverseSentence();
    return 0;
}

void reverseSentence() {
    char c;
    scanf("%c", &c);
    if (c != '\n') {
        reverseSentence();
        printf("%c", c);
    }
}
```
----------------------------------------

# Question 46

### **Question:**

> ***Write a program to Swap Numbers in Cyclic Order Using Call by Reference.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
void cyclicSwap(int *a, int *b, int *c);
int main() {
    int a, b, c;

    printf("Enter a, b and c respectively: ");
    scanf("%d %d %d", &a, &b, &c);

    printf("Value before swapping:\n");
    printf("a = %d \nb = %d \nc = %d\n", a, b, c);

    cyclicSwap(&a, &b, &c);

    printf("Value after swapping:\n");
    printf("a = %d \nb = %d \nc = %d", a, b, c);

    return 0;
}

void cyclicSwap(int *n1, int *n2, int *n3) {
    int temp;
    // swapping in cyclic order
    temp = *n2;
    *n2 = *n1;
    *n1 = *n3;
    *n3 = temp;
}
```
----------------------------------------

# Question 47

### **Question:**

> ***Write a program to Find Largest Number Using Dynamic Memory Allocation.***

---------------------------------------

<strong>Solution: </strong>

```c

#include <stdio.h>
#include <stdlib.h>
int main() {
    int num;
    float *data;
    printf("Enter the total number of elements: ");
    scanf("%d", &num);

    // Allocating memory for num elements
    data = (float *)calloc(num, sizeof(float));
    if (data == NULL) {
        printf("Error!!! memory not allocated.");
        exit(0);
    }

    // Storing numbers entered by the user.
    for (int i = 0; i < num; ++i) {
        printf("Enter Number %d: ", i + 1);
        scanf("%f", data + i);
    }

    // Finding the largest number
    for (int i = 1; i < num; ++i) {
        if (*data < *(data + i))
            *data = *(data + i);
    }
    printf("Largest number = %.2f", *data);

    return 0;
}
```
----------------------------------------

# Question 48

### **Question:**

> ***Write a program to Sort Elements in Lexicographical Order.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
#include <string.h>

int main() {
   char str[5][50], temp[50];
   printf("Enter 5 words: ");

   // Getting strings input
   for (int i = 0; i < 5; ++i) {
      fgets(str[i], sizeof(str[i]), stdin);
   }

   // storing strings in the lexicographical order
   for (int i = 0; i < 5; ++i) {
      for (int j = i + 1; j < 5; ++j) {

         // swapping strings if they are not in the lexicographical order
         if (strcmp(str[i], str[j]) > 0) {
            strcpy(temp, str[i]);
            strcpy(str[i], str[j]);
            strcpy(str[j], temp);
         }
      }
   }

   printf("\nIn the lexicographical order: \n");
   for (int i = 0; i < 5; ++i) {
      fputs(str[i], stdout);
   }
   return 0;
}
```
----------------------------------------



# Question 49

### **Question:**

> ***Write a program to Add Two Complex Numbers by Passing Structure to a Function.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
typedef struct complex {
    float real;
    float imag;
} complex;

complex add(complex n1, complex n2);

int main() {
    complex n1, n2, result;

    printf("For 1st complex number \n");
    printf("Enter the real and imaginary parts: ");
    scanf("%f %f", &n1.real, &n1.imag);
    printf("\nFor 2nd complex number \n");
    printf("Enter the real and imaginary parts: ");
    scanf("%f %f", &n2.real, &n2.imag);

    result = add(n1, n2);

    printf("Sum = %.1f + %.1fi", result.real, result.imag);
    return 0;
}

complex add(complex n1, complex n2) {
    complex temp;
    temp.real = n1.real + n2.real;
    temp.imag = n1.imag + n2.imag;
    return (temp);
}
```
----------------------------------------


# Question 50

### **Question:**

> ***Write a program to Write a Sentence to a File.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
#include <stdlib.h>

int main() {
    char sentence[1000];

    // creating file pointer to work with files
    FILE *fptr;

    // opening file in writing mode
    fptr = fopen("program.txt", "w");

    // exiting program 
    if (fptr == NULL) {
        printf("Error!");
        exit(1);
    }
    printf("Enter a sentence:\n");
    fgets(sentence, sizeof(sentence), stdin);
    fprintf(fptr, "%s", sentence);
    fclose(fptr);
    return 0;
}
```
----------------------------------------

# Question 51

### **Question:**

> ***Write a program to Read a Line From a File and Display it.***

---------------------------------------

<strong>Solution: </strong>

```c

#include <stdio.h>
#include <stdlib.h> // For exit() function
int main() {
    char c[1000];
    FILE *fptr;
    if ((fptr = fopen("program.txt", "r")) == NULL) {
        printf("Error! opening file");
        // Program exits if file pointer returns NULL.
        exit(1);
    }

    // reads text until newline is encountered
    fscanf(fptr, "%[^\n]", c);
    printf("Data from the file:\n%s", c);
    fclose(fptr);

    return 0;
}
```
----------------------------------------

# Question 52

### **Question:**

> ***Write a program to Store Data in Structures Dynamically.***

---------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
#include <stdlib.h>
struct course {
    int marks;
    char subject[30];
};

int main() {
    struct course *ptr;
    int i, noOfRecords;
    printf("Enter the number of records: ");
    scanf("%d", &noOfRecords);

    // Memory allocation for noOfRecords structures
    ptr = (struct course *)malloc(noOfRecords * sizeof(struct course));
    for (i = 0; i < noOfRecords; ++i) {
        printf("Enter the name of the subject and marks respectively:\n");
        scanf("%s %d", (ptr + i)->subject, &(ptr + i)->marks);
    }

    printf("Displaying Information:\n");
    for (i = 0; i < noOfRecords; ++i)
        printf("%s\t%d\n", (ptr + i)->subject, (ptr + i)->marks);

    return 0;
}

```
----------------------------------------




# Question 53
### **Question:**

> ***Write a program to Check if a Matrix is Invertible.***

----------------------------------------

<strong>Solution: </strong>

```c
#include<stdio.h>
 int main(){
 
  int a[3][3], i, j;
 
  long determinant;
  printf("Enter the 9 elements of matrix: ");
  for(i = 0 ;i < 3;i++)
      for(j = 0;j < 3;j++)
           scanf("%d", &a[i][j]);
 
  printf("\nThe matrix is\n");
  for(i = 0;i < 3; i++){
      printf("\n");
      for(j = 0;j < 3; j++)
           printf("%d\t", a[i][j]);
  }
  determinant = a[0][0] * ((a[1][1]*a[2][2]) - (a[2][1]*a[1][2])) -a[0][1] * (a[1][0]
   * a[2][2] - a[2][0] * a[1][2]) + a[0][2] * (a[1][0] * a[2][1] - a[2][0] * a[1][1]);
   if ( determinant == 0)
       printf("\nMatrix is NOT invertible");
   else
       printf("\nThe given matrix has an inverse!!!");
   return 0;
}
```
----------------------------------------

# Question 54

### **Question:**

> ***Write a program to Compute Determinant of a Matrix.***

----------------------------------------

<strong>Solution: </strong>

```c
#include<stdio.h>
 
int main(){
 
  int a[3][3], i, j;
 
  long determinant;
  printf("Enter the 9 elements of matrix: ");
  for(i = 0 ;i < 3;i++)
      for(j = 0;j < 3;j++)
           scanf("%d", &a[i][j]);
 
  printf("\nThe matrix is\n");
  for(i = 0;i < 3; i++){
      printf("\n");
      for(j = 0;j < 3; j++)
           printf("%d\t", a[i][j]);
  }
 
  determinant = a[0][0] * ((a[1][1]*a[2][2]) - (a[2][1]*a[1][2])) -a[0][1] * (a[1][0]
   * a[2][2] - a[2][0] * a[1][2]) + a[0][2] * (a[1][0] * a[2][1] - a[2][0] * a[1][1]);
 
  printf("\nDeterminant of 3X3 matrix: %ld", determinant);
 
   return 0;
}
```
----------------------------------------

# Question 55

### **Question:**

> ***Write a program to Implement Hash Tables.***

----------------------------------------

<strong>Solution: </strong>

```c
#include<stdio.h>
#include<stdlib.h>
 
struct data 
{
	int key;
	int value;
};
 
struct data *array;
int capacity = 10;
int size = 0;
 
/* this function gives a unique hash code to the given key */
int hashcode(int key)
{
	return (key % capacity);
}
 
/* it returns prime number just greater than array capacity */
int get_prime(int n)
{
	if (n % 2 == 0) 
        {
		n++;
	}
	for (; !if_prime(n); n += 2);
 
	return n;
}
 
/* to check if given input (i.e n) is prime or not */
int if_prime(int n)
{
	int i;
	if ( n == 1  ||  n == 0) 
        {
		return 0;
	}
	for (i = 2; i < n; i++) 
        {
		if (n % i == 0) 
                {
			return 0;
		}
	}
	return 1;
}
 
void init_array()
{
	int i;
	capacity = get_prime(capacity);
	array = (struct data*) malloc(capacity * sizeof(struct data));
	for (i = 0; i < capacity; i++) 
        {
		array[i].key = 0;
		array[i].value = 0;
	}
}
 
/* to insert a key in the hash table */
void insert(int key)
{
	int index = hashcode(key);
	if (array[index].value == 0) 
        {
		/*  key not present, insert it  */
		array[index].key = key;
		array[index].value = 1;
		size++;
		printf("\n Key (%d) has been inserted \n", key);
	}
	else if(array[index].key == key) 
        {
		/*  updating already existing key  */
		printf("\n Key (%d) already present, hence updating its value \n", key);
		array[index].value += 1;
	}
	else
        {
		/*  key cannot be insert as the index is already containing some other key  */
		printf("\n ELEMENT CANNOT BE INSERTED \n");
	}
}
 
/* to remove a key from hash table */
void remove_element(int key)
{
	int index  = hashcode(key);
	if(array[index].value == 0)
        {
		printf("\n This key does not exist \n");
	}
	else {
		array[index].key = 0;
		array[index].value = 0;
		size--;
		printf("\n Key (%d) has been removed \n", key);
	}
}
 
/* to display all the elements of a hash table */
void display()
{
	int i;
	for (i = 0; i < capacity; i++)
        {
		if (array[i].value == 0)
                {
			printf("\n Array[%d] has no elements \n");
		}
		else 
                {
			printf("\n array[%d] has elements -:\n key(%d) and value(%d) \t", i, array[i].key, array[i].value);
		}
	}
}
 
int size_of_hashtable()
{
	return size;
}
 
void main()
{
	int choice, key, value, n, c;
	clrscr();
 
	init_array();
 
	do {
		printf("\n Implementation of Hash Table in C \n\n");
		printf("MENU-:  \n1.Inserting item in the Hash Table" 
                               "\n2.Removing item from the Hash Table"
		               "\n3.Check the size of Hash Table" 
                               "\n4.Display a Hash Table"
		       "\n\n Please enter your choice -:");
 
		scanf("%d", &choice);
 
		switch(choice) 
                {
 
		case 1:
 
		      printf("Inserting element in Hash Table\n");
		      printf("Enter key -:\t");
		      scanf("%d", &key);
		      insert(key);
 
		      break;
 
		case 2:
 
		      printf("Deleting in Hash Table \n Enter the key to delete-:");
		      scanf("%d", &key);
		      remove_element(key);
 
		      break;
 
		case 3:
 
		      n = size_of_hashtable();
		      printf("Size of Hash Table is-:%d\n", n);
 
		      break;
 
		case 4:
 
		      display();
 
		      break;
 
		default:
 
		       printf("Wrong Input\n");
 
		}
 
		printf("\n Do you want to continue-:(press 1 for yes)\t");
		scanf("%d", &c);
 
	}while(c == 1);
 
	getch();
 
}

```
----------------------------------------

 
# Question 56

### **Question:**

> ***Write a program to Check if a Matrix is a Sparse Matrix.***

----------------------------------------

<strong>Solution: </strong>

```c
#include <stdio.h>
 
void main ()
{
    int matrix[10][10];
    int i, j, m, n;
    int sparse_counter = 0;
 
    printf("Enter the order of the matix \n");
    scanf("%d %d", &m, &n);
    printf("Enter the elements of the matix \n");
    for (i = 0; i < m; ++i)
    {
        for (j = 0; j < n; ++j)
        {
            scanf("%d", &matrix[i][j]);
            if (matrix[i][j] == 0)
            {
                ++sparse_counter;
            }
        }
    }
    if (sparse_counter > ((m * n) / 2))
    {
        printf("The given matrix is Sparse Matrix !!! \n");
    }
    else
        printf("The given matrix is not a Sparse Matrix \n");
    printf("There are %d number of Zeros.", sparse_counter);
}
```
----------------------------------------

 
# Question 57

### **Question:**

> ***Write a program to Perform Complex Number Multiplication.***

----------------------------------------

<strong>Solution: </strong>

```c
#include<stdio.h>
typedef struct COMPLEX{
    int a;
    int b;
}Complex;
Complex multiply(Complex, Complex);
int main(){
    int a1, b1, a2, b2;
    Complex x, y, z;
    printf("Enter first complex number : ");
    scanf("%d+%di", &a1, &b1);
    printf("\nEnter second complex number : ");
    scanf("%d+%di", &a2, &b2);
    x.a = a1;
    x.b = b1;
    y.a = a2; 
    y.b = b2;
    z = multiply(x, y);
    printf("\nAfter multiplication: %d+%di", z.a, z.b);
    return 0;
}
Complex multiply(Complex x, Complex y){
    Complex z;
    z.a = x.a * y.a - x.b * y.b;
    z.b = x.a * y.b + x.b * y.a;
    return z;
}
```
----------------------------------------
# Question 58

### **Question:**

> ***Write a program to Generate Random Hexadecimal Bytes.***

----------------------------------------

<strong>Solution: </strong>

```c
#include <time.h>
#include <stdio.h>
#include <stdlib.h>
 
int main(void)
{
    int length;
    char str[] = "0123456789ABCDEF";
    /* Seed number for rand() */
    srand((unsigned int) time(0) + getpid());
    length = rand() % 15 + 8;
 
    while(length--) {
        putchar(str[rand() % 16]);
        srand(rand());
    }
    printf("\n");
 
    return EXIT_SUCCESS;
}
```
----------------------------------------


</br>

<h2> Papers  </h2>

<ul>

 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(1).pdf" style="text-decoration:none;">C and C++: a Case for Compatibility</a></li>


 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(2).pdf" style="text-decoration:none;">Loop Patterns in C Programs</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(3).pdf" style="text-decoration:none;">The Improved Methods of Teaching Practice Based on C Language Programming</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(4).pdf" style="text-decoration:none;">Bad Is Stronger Than Good</a></li>                              
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(5).pdf" style="text-decoration:none;">The Basics of C Programming</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(6).pdf" style="text-decoration:none;">A Serious Game for Learning C Programming Language Concepts Using Solo Taxonomy</a></li>
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(7).pdf" style="text-decoration:none;">Assisted learning of C programming through automated program repair and feed-back generation</a></li>

 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(8).pdf" style="text-decoration:none;"> 
An Introduction to C and GUI Programming</a></li>
   <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(9).pdf" style="text-decoration:none;">
C Programming </a></li>
  
   
 <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(10).pdf" style="text-decoration:none;">An Introduction to the C Programming Language and Software Design</a></li>                              
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(11).pdf" style="text-decoration:none;">C Language Tutorial</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(12).pdf" style="text-decoration:none;">Essential C</a></li>
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(13).pdf" style="text-decoration:none;">The pitfalls of verifying floating-point computations</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(14).pdf" style="text-decoration:none;">The Development of the C Language</a></li>
                              
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(15).pdf" style="text-decoration:none;">Assessing Programming Language Impact on Development and Maintenance: A Study on C and C++</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(16).pdf" style="text-decoration:none;">Introduction to C programming</a></li>

  <li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(17).pdf" style="text-decoration:none;">
Some Were Meant for C</a></li>   
  
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(18).pdf" style="text-decoration:none;">Understanding Integer Overflow in C/C++</a></li> 

  
<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(19).pdf" style="text-decoration:none;">A Tutorial on Pointers and Arrays in C</a></li> 

<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(20).pdf" style="text-decoration:none;"> PVC.js: visualizing C programs on web browsers for novices</a></li>

<li><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/cpj(21).pdf" style="text-decoration:none;">Teaching Security in Introductory C-Programming Courses</a></li>
</ul>

</br>


<h3>Books:</h3>
<hr>

<ul>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/pb(1).pdf" style="text-decoration:none;">The C Puzzle Book </a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/pb(2).pdf" style="text-decoration:none;">Functional C</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/pb(3).pdf" style="text-decoration:none;">C: The Complete Reference</a></b></li>
 <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/pb(4).pdf" style="text-decoration:none;">C: A Reference Manual </a></b></li>                              
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/pb(5).pdf" style="text-decoration:none;">Let Us C </a></b></li>
                                
 <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/pb(6).pdf" style="text-decoration:none;">Mastering Algorithms with C</a></b></li>
                          
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/pb(7).pdf" style="text-decoration:none;">C: How to Program </a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/pb(8).pdf" style="text-decoration:none;">Test Your C Skills</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/pb(9).pdf" style="text-decoration:none;">The C Programming Language </a></b></li>
                                
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/pb(10).pdf" style="text-decoration:none;">C For Dummies</a></b></li>  

<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/avc(1).pdf" style="text-decoration:none;">Sams Teach Yourself C in 21 Days </a></b></li>
 <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/avc(2).pdf" style="text-decoration:none;">C Programming: The ultimate way to learn the fundamentals of the C language</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/avc(3).pdf" style="text-decoration:none;">C Programming Tutorial</a></b></li>
 <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/avc(4).pdf" style="text-decoration:none;">Example C Programming Codes </a></b></li>                              
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/avc(5).pdf" style="text-decoration:none;">C Tutorial</a></b></li>
                                
 <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/avc(6).pdf" style="text-decoration:none;">Learn C the Hard Way</a></b></li>
                          
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/avc(7).pdf" style="text-decoration:none;">Expert C Programming: Deep C Secrets </a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/avc(8).pdf" style="text-decoration:none;">C in Depth</a></b></li>
                                <li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/avc(9).pdf" style="text-decoration:none;">Practical C Programming</a></b></li>
                                
<li><b><a target="_blank" href="https://github.com/manjunath5496/Beginner-C-Exercises/blob/master/avc(10).pdf" style="text-decoration:none;">C Traps and Pitfalls</a></b></li> 












 </ul>
	

