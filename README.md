# **PROGRAMMING FOR PROBLEM SOLVING** 
## NAME- *Ramesh khanal*
## UNIVERSITY ROLL NO.- *2005097* 
## COLLEGE ROLL NO- *2030073* 
## BRANCH- *Mechanical* 
## SECTION- *ME-B* ![LOGO](https://blog.coachingkaro.org/wp-content/uploads/2019/07/logo.jpg) 

# **GURU NANAK DEV ENGINEERING COLLEGE, LUDHIANA** 




S.no | Program Name 
----- | -----------
1 | Program to print a content sing printf & puts
2 | Program to use different data types (int, Float, Char)
3 | Program to use arithmetic operators
4 | Program to use logical operators
5 | Program to use relational operators
6 | Program to use increment and decrement operators
7 | Program to use conditional statements: if-else, if else ladder
8 | Program to use for loop, nested for loop
9 | Program to use while loop, do-while loop
10 | Program to use switch (break and continue)
11 | Program to implement and use functions
12 | Program to use arrays







*Program:1* **Program to print a content 
		using printf and puts**





```
// C program to show the use of puts

#include <stdio.h>

int main()
{

    puts("GNDEC");

    puts("LUDHIANA");
 

    getchar();

    return 0;
}
```


**Output:**
```
GNDEC
LUDHIANA
```


```
// C program to show the use of printf

#include <stdio.h>
int main()
{

    

    printf("GNDEC LUDHIANA");

    getchar();

    return 0;

}
```

**Output:**
```
GNDEC LUDHIANA
```

*Program 2* **Program to use different data types
              (int,float,char)**
              
```
#include <stdio.h>

int main()
{

    int a = 1;

    char b = 'G';

    double c = 3.14;

    printf("Hello World!\n");
 

    // printing the variables defined 

    // above along with their sizes

    printf("Hello! I am a character. My value is %c and "

           "my size is %lu byte.\n",

           b, sizeof(char));

    // can use sizeof(b) above as well
 

    printf("Hello! I am an integer. My value is %d and "

           "my size is %lu  bytes.\n",

           a, sizeof(int));
          
          // can use sizeof(a) above as well
 

    printf("Hello! I am a double floating point variable."

           " My value is %lf and my size is %lu bytes.\n",

           c, sizeof(double));

    // can use sizeof(c) above as well
 

    printf("Bye! See you soon. :)\n");

    return 0;
}
```


**Output:** 
```
Hello World!
Hello! I am a character. My value is G and my size is 1 byte.
Hello! I am an integer. My value is 1 and my size is 4  bytes.
Hello! I am a double floating point variable. My value is 3.140000 and my size i
s 8 bytes.
Bye! See you soon. :)
```





*Program 3* **Program to use arithmetic operators.**

```
/* Program to Perform Arithmetic Operations in C */

#include<stdio.h>

int main()
{
 int a = 12, b = 3;
 int addition, subtraction, multiplication, division, modulus;
 
 addition = a + b;        //addition of 3 and 12
 subtraction = a - b;    //subtract 3 from 12
 multiplication = a * b; //Multiplying both
 division = a / b;       //dividing 12 by 3 (number of times)
 modulus = a % b;       //calculation the remainder
 
 printf("Addition of two numbers a, b is : %d\n", addition);
 printf("Subtraction of two numbers a, b is : %d\n", subtraction);
 printf("Multiplication of two numbers a, b is : %d\n", multiplication);
 printf("Division of two numbers a, b is : %d\n", division);
 printf("Modulus of two numbers a, b is : %d\n", modulus);

}
```

**Output:**
```
Additions of two numbers a,b is : 15
Subtraction of two numbers a,b is : 9
Multiplication of two numbers a,b is: 36
Division of two numbers a, b is : 4
Modulus of two numbers a, b is : 0
```



*Program 4*  **Program to use logical operators.**
```
#include <stdio.h>
main() {

   int a = 5;
   int b = 20;
   int c ;

   if ( a && b ) {
      printf("Line 1 - Condition is true\n" );
   }
	
   if ( a || b ) {
      printf("Line 2 - Condition is true\n" );
   }
   
   /* lets change the value of  a and b */
   a = 0;
   b = 10;
	
   if ( a && b ) {
      printf("Line 3 - Condition is true\n" );
   } else {
      printf("Line 3 - Condition is not true\n" );
   }
	
   if ( !(a && b) ) {
      printf("Line 4 - Condition is true\n" );
   }
	
}
```

**Output:**
```
Line 1 - Condition is true
Line 2 - Condition is true
Line 3 - Condition is not true
Line 4 - Condition is true
```






*Program 5* **Program to use relational operators.**
```
#include <stdio.h>
main() {

   int a = 21;
   int b = 10;
   int c ;

   if( a == b ) {
      printf("Line 1 - a is equal to b\n" );
   } else {
      printf("Line 1 - a is not equal to b\n" );
   }
	
   if ( a < b ) {
      printf("Line 2 - a is less than b\n" );
   } else {
      printf("Line 2 - a is not less than b\n" );
   }
	
   if ( a > b ) {
      printf("Line 3 - a is greater than b\n" );
   } else {
      printf("Line 3 - a is not greater than b\n" );
   }
   
   /* Lets change value of a and b */
   a = 5;
   b = 20;
	
   if ( a <= b ) {
      printf("Line 4 - a is either less than or equal to  b\n" );
   }
	
   if ( b >= a ) {
      printf("Line 5 - b is either greater than  or equal to b\n" );
   }
}
```
**Output:**
```
Line 1 - a is not equal to b
Line 2 - a is not less than b
Line 3 - a is greater than b
Line 4 - a is either less than or equal to  b
Line 5 - b is either greater than  or equal to b
```



*Program 6*  **Program to use increment and decrement operators.**

**// Increment operator in c**
```
#include <stdio.h>
int main()
{
     int i=1;
     while(i<10)
     {
         printf("%d ",i);
         i++;
     }    
}
```

**Output:**
```
1 2 3 4 5 6 7 8 9
```

// Decrement operator in C
```
#include <stdio.h>
int main()
{
    int i=20;
    while(i>10)
    {
         printf("%d ",i);
         i--;
    }    
}
```


**Output:**

```
20 19 18 17 16 15 14 13 12 11
```


*Program 7*  **Program to use conditional statements: if-else, if else ladder**


```
#include <stdio.h> 
int main() 
{ 
	int i = 20; 

	// Check if i is 10 
	if (i == 10) 
		printf("i is 10"); 

	// Since i is not 10 
	// Check if i is 15 
	else if (i == 15) 
		printf("i is 15"); 

	// Since i is not 15 
	// Check if i is 20 
	else if (i == 20) 
		printf("i is 20"); 

	// If none of the above conditions is true 
	// Then execute the else statement 
	else
		printf("i is not present"); 

	return 0; 
} 
```

__Output:__
```
i is 20
```



// C program to illustrate nested-if statement 
```
#include <stdio.h> 

int main() 
{ 
	int i = 25; 

	// Check if i is between 0 and 10 
	if (i >= 0 && i <= 10) 
		printf("i is between 0 and 10"); 

	// Since i is not between 0 and 10 
	// Check if i is between 11 and 15 
	else if (i >= 11 && i <= 15) 
		printf("i is between 11 and 15"); 

	// Since i is not between 11 and 15 
	// Check if i is between 16 and 20 
	else if (i >= 16 && i <= 20) 
		printf("i is between 16 and 20"); 

	// Since i is not between 0 and 20 
	// It means i is greater than 20 
	else
		printf("i is greater than 20"); 
} 
```
**Output:**
```
i is greater than 20
```




*Program 8* **Program to use for loop, nested for loop.**

```
#include <stdio.h>
int main() {
  int i;

  for (i = 1; i < 11; ++i)
  {
    printf("%d ", i);
  }
  return 0;
}
```
**Output**
```
1 2 3 4 5 6 7 8 9 10
```



*Program 9*  **Program to use while loop, do-while loop.**

```
#include <stdio.h>
int main()
{
    int i = 1;
    
    while (i <= 5)
    {
        printf("%d\n", i);
        ++i;
    }

    return 0;
}
```
**Output**
```
1
2
3
4
5
```

**do-while loop**


```
#include <stdio.h>
int main()
{
    double number, sum = 0;

    // the body of the loop is executed at least once
    do
    {
        printf("Enter a number: ");
        scanf("%lf", &number);
        sum += number;
    }
    while(number != 0.0);

    printf("Sum = %.2lf",sum);

    return 0;
}
```
**Output**
```
Enter a number: 1.5
Enter a number: 2.4
Enter a number: -3.4
Enter a number: 4.2
Enter a number: 0
Sum = 4.70
```




*Program 10*  **Program to use switch statement.**

```
#include <stdio.h>
int main() {
    char operator;
    double n1, n2;

    printf("Enter an operator (+, -, *, /): ");
    scanf("%c", &operator);
    printf("Enter two operands: ");
    scanf("%lf %lf",&n1, &n2);

    switch(operator)
    {
        case '+':
            printf("%.1lf + %.1lf = %.1lf",n1, n2, n1+n2);
            break;

        case '-':
            printf("%.1lf - %.1lf = %.1lf",n1, n2, n1-n2);
            break;

        case '*':
            printf("%.1lf * %.1lf = %.1lf",n1, n2, n1*n2);
            break;

        case '/':
            printf("%.1lf / %.1lf = %.1lf",n1, n2, n1/n2);
            break;

        // operator doesn't match any case constant +, -, *, /
        default:
            printf("Error! operator is not correct");
    }

    return 0;
}
```
**Output**
```
Enter an operator (+, -, *,): -
Enter two operands: 32.5
12.4
32.5 - 12.4 = 20.1
```



*Program 11*   **Program to implement and use functions**
```
#include <stdio.h>
int addition(int num1, int num2)
{
     int sum;
     /* Arguments are used here*/
     sum = num1+num2;

     /* Function return type is integer so we are returning
      * an integer value, the sum of the passed numbers.
      */
     return sum;
}

int main()
{
     int var1, var2;
     printf("Enter number 1: ");
     scanf("%d",&var1);
     printf("Enter number 2: ");
     scanf("%d",&var2);

     /* Calling the function here, the function return type
      * is integer so we need an integer variable to hold the
      * returned value of this function.
      */
     int res = addition(var1, var2);
     printf ("Output: %d", res);

     return 0;
}
```
**Output:**
```
Enter number 1: 100
Enter number 2: 120
Output: 220
```





*Program 12*   **Program to use arrays**
```
// Program to take 5 values from the user and store them in an array
// Print the elements stored in the array
#include <stdio.h>

int main() {
  int values[5];

  printf("Enter 5 integers: ");

  // taking input and storing it in an array
  for(int i = 0; i < 5; ++i) {
     scanf("%d", &values[i]);
  }

  printf("Displaying integers: ");

  // printing elements of an array
  for(int i = 0; i < 5; ++i) {
     printf("%d\n", values[i]);
  }
  return 0;
}
```
**Output**
```
Enter 5 integers: 1
-3
34
0
3
Displaying integers: 1
-3
34
0
3
```
