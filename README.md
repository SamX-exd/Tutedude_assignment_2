# Tutedude_assignment_2
Here is the 2nd assignment. 
This assignment has 2 Tasks. 1st is for the 'if-else' statement and the 2nd is for the  'for-loop'.


Task 1:
1. num = int(input("Enter a number: "))

.The program asks the user to enter a number.

.'input()' takes the value.

.'int()' converts that value into an integer so we can do math with it.

Example:
-> If the user types 7, then num becomes 7.

2. if num % 2 == 0:

.'%' is called the modulus operator.

.It gives the remainder when one number is divided by another.

> So 'num % 2' means:

.Divide 'num' by 2 and check the remainder.

.If remainder is 0, the number is even.

3. print(f"{num} is an even number.")

.This line runs only when the if condition is true.

.It prints that the number is even.

4. else:

.If the 'if condition' is NOT true, this part runs.

.That means the remainder is not 0 → number is odd.

5. print(f"{num} is an odd number.")

.This prints the result if the number is odd


_______x_______x_______x_______x_______x_______x_______x_______x_______x_______x_______x_______x_______x_______x_______x_______x_______x_______x_______x_______x_______x_______x_______x__



#Task 2:
1. total = 0

.This creates a variable named total.

.It is set to 0 because we haven’t added any numbers yet.

.This variable will store the final sum.

2. for sum in range(1, 51):

.This is a for loop that runs from 1 to 50.

."range(1, 51)" generates numbers starting at 1 and ending at 50 (because 51 is not included).

.In each loop, the variable "sum" holds the current number in the sequence.

>So the loop runs with:

sum = 1
sum = 2
sum = 3
...
sum = 50

3. total += sum

.This line means:

.total = total + sum


> So what happens?

.At first: total = 0

->Loop 1: total = 0 + 1 = 1

->Loop 2: total = 1 + 2 = 3

->Loop 3: total = 3 + 3 = 6

-> .... continues until 50

> By the end of the loop, "total" stores the sum of all numbers from 1 to 50.

4. print("The sum of numbers from 1 to 50 is:", total)

After the loop finishes, the program prints the final value stored in "total".

#NOTE : We have to end the INDENTATION before writting the "print" statement otherwise the "print" statement will run for 50 time each time adding the number 1 by 1
















