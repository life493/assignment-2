ASSIGNMENT-2

TASK 1-CHECK IF A NUMBER IS ODD OR EVEN USING IF-ELSE STATEMENT 
DESCRIPTION-The following python program takes a number from the user and checks whether the number is odd or even using if-else statement .

STEP 1-TAKING NUMBER FROM THE USER 
In the first step we take the input from the user using the built-in input() function.
num=int(input("Enter a number:")
Here, the in-built function takes the input and stores it in a variable named"num".

STEP 2-CHECKING WHETHER THE NUMBER IS ODD OR EVEN (USING IF-ELSE STATEMENT).
In the next step we now check whether the number is odd or even using if-else statement .
if num%2==0:
    print(num,"is a even number")
else:
    print(num ,"is a odd number")

Now we know that even numbers are divisible by 2 that is leave remainder 0 and odd numbers are not that is they leave some remainder .
Thus in the in the second line of code we have used this statement (num%2==0) to see whether it will give remainder 0 when divided by 2.If it gives reminder 0 then it is a even number else it is a odd number, and print the result accordingly.
NOTE-% it is used to represent the remainder 


TASK 2- SUM OF INTEGERS FROM 1 TO 50 USING FOR LOOP
DESCRIPTION-The following python code calculates the sum of integers from 1 to 50 (using a for loop).

STEP 1-INTIALIZING SUM
In the first step ,we use the variable 'sum" and assign it to 0 which will help to store the cumulative sum of numbers 
sum=0

STEP 2 -USING THE FOR LOOP
In the second step we use the for loop:
for i in range (1,51)
This starts a for loop and genrates the numbers from 1 to 50 
The variable 'i' takes the number from 1 to 50 one by one .

STEP 3 -ITERATING 
In the next step we iterate,that is sum+=1 which short for sum=sum+i 
which adds the current value of i to the varible 'sum'.For eg-
ITERATION 1-i=1,sum=0+1=1   (value of sum is 0 ,which we have declared earlier)
ITERATION 2-i=2,sum=0+2=2
ITERATION 3-i=3,sum=0+3=3
ITERATION 4-i=4,sum=0+4=4
........
ITERATION 50-i=50,sum=50+0=50

STEP 4- FINAL OUTPUT 
In the last step we will use the print() function to print the sum 
print("The sum of integers from 1 to 50 is:",sum)




