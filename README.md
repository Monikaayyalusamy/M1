# EX-01-Datatypes-Operators

## AIM:
Write a C program to read a special symbol from the user and display the same symbol.

## ALGORITHM:
```
1.Start
2.Declare a variable symbol of type char.
3.Read a single character input from the user and store it in symbol.
4.Display the value stored in symbol.
5.End
```

## PROGRAM:
```
#include <stdio.h>
int main()
{
    char symbol;
    scanf("%c",&symbol);
    printf("%c\n",symbol);
return 0;
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/1b889259-c8c3-40a3-923d-f82b54365cdc)

## RESULT:
Thus the program to read a special symbol from the user and display the same symbol has been executed successfully.


# EX-02- Conditional-Statements

## AIM:
Write a C program to read a, b value and find the greatest value using  if-else

# ALGORITHM:
```
1.Start
2.Declare two integer variables: a and b.
3.Read two integers from the user and store them in a and b.
4.Compare if a < b
 If true, then print "B is greatest."
 Else, print "A is greatest."
5.End
```

# PROGRAM:
```
#include <stdio.h>
int main()
{
    int a,b;
    scanf("%d %d",&a,&b);
    if (a<b)
    {
        printf("B is greatest.");
    }
    else
    {
        printf("A is greatest.");
    }
}    
```

# OUTPUT:
![image](https://github.com/user-attachments/assets/f9ec960f-ae66-4e02-b0ad-a7995765e0bf)


# RESULT:
Thus the program to read a, b value and find the greatest value using  if-else has been executed successfully.
 
 
# EX-03- Operators-Expressions

## AIM:
Write a C program to swap (For ex: a=200,b=-300 into a=-300,b=200) two values without using a third variable.

## ALGORITHM:
```
1.Start
2.Declare two integer variables: a and b.
3.Read two integers from the user and store them in a and b.
4.Display the values of a and b before swapping.
5.Swap Logic Without Temporary Variable:
 Set a = a + b
 Set b = a - b
 Set a = a - b
6.Display the values of a and b after swapping.
7.End
```

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int a,b;
    scanf("%d %d",&a,&b);
    printf("Numbers before swapping: %d %d \n",a,b);
    a=a+b;
    b=a-b;
    a=a-b;
    printf("Numbers after swapping: %d %d",a,b);
    
    return 0;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/89ecd2d1-5908-4596-8b63-d7eb1ce716be)


## RESULT:
Thus the program to swap (For ex: a=200,b=-300 into a=-300,b=200) two values without using a third variable has been executed successfully.


# EX-04- Using Conditional Statements

## AIM:
Write a C program to read the age of a person and determine whether she is eligible for marriage( assume marriage age is greater than or equal to 18) . 

## ALGORITHM:
```
1.Start
2.Declare an integer variable a.
3.Read the value of a (age) from the user.
4.Check if a >= 18
 If true, print "she is eligible for marriage".
 If false, do nothing (no message is printed).
5.End
```

## PROGRAM:
```
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if(a>=18)
    {
        printf("she is eligible for marriage");
    }
  
    
 return 0;   
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/c8f97bbc-7268-48b7-ac6c-316ed4b129c2)


## RESULT:
Thus the program to read the age of a person and determine whether she is eligible for marriage( assume marriage age is greater than or equal to 18)  has been executed successfully


# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 

## AIM:
Write a C program to find simple interest.  Note: Inputs are principle, year and rate.


## ALGORITHM:
```
1.Start
2.Declare variables p, y, r, s (all float).
3.Read input values for:
4.Principal (p)
5.Number of years (y)
6.Rate of interest (r)
7.Compute simple interest using:
 s = (p * r * y) / 100
8.Display result: "Simple Interest = <value of s>"
9.End
```

## PROGRAM:
```
#include <stdio.h>
int main()
{
    float p,y,r,s;
    scanf("%f%f%f",&p,&y,&r);
    s=(p*r*y)/100;
    printf("Simple Interest = %.2f",s);
    return 0;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/cddfb5e6-3513-4ad6-a093-8b8341c59889)


## RESULT:

The program to find simple interest has been executed successfully.


