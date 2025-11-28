Programming language: JAVA

Program-1.java
This program is a simple calculator implemented using Java.

Features

The calculator performs the following operations using a separate Calculator class:

Addition

Subtraction

Multiplication

Division (with zero-division check)


Inputs

The program accepts:

a – first number (double)

b – second number (double)

operation – type of operation (string)


Output

Based on the selected operation, the program prints the result of the calculation.

Programming language: JAVA

Program-2.java
This program generates a series of numbers based on a single integer input.

Description

Given an integer a, the program prints a sequence of odd numbers starting from 1 until the sequence contains a numbers.

Example

If input is:

a = 1 → output: 1

a = 2 → output: 1, 3

a = 4 → output: 1, 3, 5, 7


Logic Used

Start with the first odd number: 1

Repeatedly add 2 to generate the next odd number

Print exactly a numbers in the series


Input

a → integer


Output

Sequence of Odd numbers Programming language: JAVA

Program-3.java
This program generates a sequence of odd numbers based on a single integer input.

Description

Given an integer a, the program prints all odd numbers starting from 1 up to the maximum odd number less than or equal to a.

Program Behavior

If the input number a is even, it is reduced by 1 to make it odd.

The program then prints the sequence of odd numbers from 1 up to the adjusted value of a.


Logic Used

Start with the first odd number: 1

Increment the value by 2 to generate the next odd number

Continue until the value reaches the largest odd number ≤ a


Input

a → integer


Output

A sequence of odd numbers starting from 1 up to the largest odd number less than or equal to a.Program-4.java
This program counts how many numbers in the input list are divisible by each number from 1 to 9.

Description

The user enters the number of elements and then the list of integers.

For each integer, the program checks divisibility by every number from 1 to 9.

A HashMap is used to store and update the count of how many input values are divisible by each key (1–9).


Logic Used

1. Read n elements into an array.


2. Loop through each element and test divisibility by numbers 1 to 9.


3. If divisible, increment the corresponding count in the map using map.getOrDefault().


4. Display the final dictionary (map) with the divisibility counts.



Input

n → total number of elements

List of n integers


Output

A dictionary-style map showing:

Key: number from 1 to 9

Value: how many input elements are divisible by that key
