
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.

## PROGRAM:

```
#include <stdio.h>

int main() {
    char ch1, ch2, ch3;

    scanf("%c %c %c", &ch1, &ch2, &ch3);

    printf("The reverse of %c%c%c is %c%c%c\n", ch1, ch2, ch3, ch3, ch2, ch1);

    return 0;
}
```

## OUTPUT:



![437938126-13678b3b-4c79-48fc-b0d2-953d218f4c0b](https://github.com/user-attachments/assets/1c001d8d-7345-4677-99d8-8c9dabd7c366)





## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether A is positive number or not.

# ALGORITHM:
1.	Declare a variable to store the input value A.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the value of A is greater than zero.
4.	If A is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's not a positive number.
6.End the program.

# PROGRAM:
```
#include <stdio.h>
int main()
{
    int a;
    scanf("%d",&a);
    if (a>=0)
    {
        printf("Number is positive.");
    }
    else
    {
        printf("Number is negative.");
    }
    return 0;
}
```

# OUTPUT:



![437278824-63b542d8-8236-4737-a42d-dbad7d514e51](https://github.com/user-attachments/assets/d6ec1e1b-4128-407c-8c66-96f4a65875a6)








# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:

```
#include <stdio.h>
int main(){
    int a,b;
    scanf("%d %d",&a,&b);
    (a>b)?
    printf("Maximum between %d and %d is %d",a,b,a):
    printf("Maximum between %d and %d is %d",a,b,b);
    
    }


```

## OUTPUT:
![image](https://github.com/user-attachments/assets/72404e23-f618-4b1c-9790-4cb54dc901c1)










## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 1.
4.	If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5.	Otherwise, print a message indicating that it's not equal to 1.
6.	End the program.

## PROGRAM:

```
#include <stdio.h>
int main(){
    int a;
    scanf("%d",&a);
    if(a==1)
       printf("TRUE");
       
   
}
```

## OUTPUT:





![437278269-85f8b25c-cf9e-4c92-a168-00cc17f13cd1](https://github.com/user-attachments/assets/c0f22b58-7328-4a6a-9891-f5b873e3f928)




	

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
```

#include <stdio.h>
int main()  
{
    float  a,b,c,tot;
    float per;
    scanf("%f%f%f",&a,&b,&c);
    tot=a+b+c;
    per=(tot*100)/300;
    if (per>=80) {
        printf("Total Marks = %.0f\nPercentage = %.2f\nDivision = First",tot,per);
        
    }
    else if (per<60 && per>=48)
    {
        printf("Total Marks = %.0f\nPercentage = %.2f\nDivision = Second",tot,per);
    }
    else if(per<36) {
        printf("Total Marks = %.0f\nPercentage = %.2f\nDivision = Fail",tot,per);
    }
    else if (per>36 && per<=40){
        printf("Total Marks = %.0f\nPercentage = %.2f\nDivision = Fail",tot,per);
    }
    else if (per>60 && per<70){
        printf("Total Marks = %.0f\nPercentage = %.2f\nDivision = Fail",tot,per);
    }
    else{
        printf("Total Marks = %.0f\nPercentage = %.2f\nDivision = Pass",tot,per);
    }
    
    return 0;
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/5fea5d75-7739-44dc-a050-05ea81bc3135)


## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

