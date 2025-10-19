
# EX-01-Datatypes-Operators
## AIM:
write a C program that reads two integers from the user and calculates the remainder when the first integer is divided by the second.

## ALGORITHM:
1. Declare three integer variables: a, b, and rem.
2. Read two integers from the user and store them in a and b.
3. Check if b is not zero to avoid division by zero.
4. Calculate the remainder using the modulus operator: rem = a % b.
5. Display the result using printf.
6. End the program.

## PROGRAM:
```
#include <stdio.h>

int main() {
      int a,b,rem;
      scanf("%d %d",&a,&b);
      rem=a%b;
      printf("Remainder of %d and %d=%d",a,b,rem);
      return 0;
}
```

## OUTPUT:
![alt text](<output 1.png>)

## RESULT:
Thus the program to read 2 integers from the user and calculates the remainder when the first integer is divided by the second has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
write a C program that reads an integer input from the user and displays the number of yards only if the input is not zero.

# ALGORITHM:
1. Declare an integer variable num.
2. Read an integer value from the user and store it in num.
3. Check if num is not equal to zero.
4. If true, print "There were <num> yards".
5. If false, do nothing.
6. End the program.


# PROGRAM:
```
#include <stdio.h>

int main() {
      int num;
      scanf("%d",&num);
      if(num!=0)
      {
          printf("There were %d yards",num);
      }
      return 0;
}
```

# OUTPUT:
![alt text](<output 2.png>)

# RESULT:
Thus the program to read an integer input from the user and display the number of yards has been executed successfully.
 
 
 
# EX-03- Operators-Expressions
## AIM:
write a C program that reads two floating-point numbers and prints the minimum of the two using the conditional (ternary) operator.

## ALGORITHM:
1. Declare three float variables: a, b, and max.
2. Read two float values from the user and store them in a and b.
3. Compare the values using the ternary operator.
4. If a < b, assign a to max.
5. Else, assign b to max.
6. Print the minimum value with three decimal places.
7. End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    float a,b,max;
    scanf("%f %f",&a,&b);
    max = (a<b)? a : b;
    printf("Minimum between %.3f and %.3f is %.3f",a,b,max);
    return 0;
}
```

## OUTPUT:
![alt text](<output 3.png>)

## RESULT:
Thus the program to find minimum between two floating point numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
write a C program that reads a person's age and determines whether they are eligible to vote based on the age criteria (18 years or older).

## ALGORITHM:
1. Declare an integer variable num to store the age.
2. Read the age from the user using scanf.
3. Check if num is greater than or equal to 18.
4. If true, print "Eligible for casting your vote".
5. If false, print "Not Eligible to caste your vote".
6. End the program.


## PROGRAM:
```
#include <stdio.h>
int main()
{
   int num;
   scanf("%d",&num);
   if(num>=18)
      {
        printf("Eligible for casting your vote");
      }
   else
     {
       printf("Not Eligible to caste your vote");
     }
 return 0;   
}
```

## OUTPUT:
![alt text](<output 4.png>)
	
## RESULT:
Thus the program check a person's age and determines whether they are eligible to vote or not has been executed successfully
 



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
write a C program that reads marks for seven subjects, calculates the total, average, and percentage, and displays the results.

## ALGORITHM:
1. Declare seven float variables a1 to a7 to store marks for each subject.
2. Declare three float variables: Total, Average, and Percentage.
3. Read seven float values from the user using scanf.
4. Calculate the total marks:Total = a1 + a2 + a3 + a4 + a5 + a6 + a7
5. Calculate the average marks:Average = Total / 7.0
6. Calculate the percentage assuming each subject is out of 100:Percentage = (Total / 700) * 100
7. Display the total, average, and percentage using printf.
8. End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    float a1,a2,a3,a4,a5,a6,a7;
    float Total,Average,Percentage;
    scanf("%f %f %f %f %f %f %f",&a1,&a2,&a3,&a4,&a5,&a6,&a7);
    Total=a1+a2+a3+a4+a5+a6+a7;
    Average=Total /7.0;
    Percentage=(Total /700)*100;
    printf("Total marks = %.2f\n",Total);
    printf("Average marks = %.2f\n",Average);
    printf("Percentage = %.2f\n",Percentage);
    return 0;
}
```

## OUTPUT:
![alt text](<output 5.png>)


## RESULT:
Thus the  program successfully takes three subject marks and calculates the total marks , average and percentage. 