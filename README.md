# 6-loops-on-c-

Aim:

To understand and use decision-making statements and loops in C++.

Tools Used:

Programiz Online C++ Compiler
Theory

Loops are used to repeat tasks in programs, helping make the code shorter and faster.

1. for Loop

Used when we know how many times to repeat.

Syntax:

for(start; condition; update) {
  // repeat this code
}

Use for loop when you know the starting and ending points clearly.



2. while Loop

Used when we don’t know how many times to repeat.

Syntax:

while(condition) {
  // repeat this code
}

Use while loop when the loop depends on user input or other changing conditions.


3. Nested for Loop

One for loop inside another. Useful for patterns or 2D arrays.

for(i...) {
  for(j...) {
    // inner code

Program 1: Print Even Numbers (0–10) Using for Loop

Algorithm:

1. Start.


2. Loop i from 0 to 10:

If i % 2 == 0, print i.



3. End loop.


4. Stop.

Program 2: Print "SIT" 5 Times Using for Loop

Algorithm:

1. Start.


2. Loop i from 0 to 4:

Print "SIT".



3. End loop.


4. Stop.
 Program 3: Print Numbers (1–20) Using while Loop

Algorithm:

1. Start.


2. Initialize n = 1.


3. While n <= 20:

Print n.

Increment n by 1.



4. Stop.

 Program 4: Password Checker Using while Loop

Algorithm:

1. Start.


2. Repeat until password length ≥ 8:

Ask user to enter password.



3. Repeat until confirmed password matches:

Ask to confirm password.



4. While user doesn’t enter 'x':

Ask for login password.

If input matches password → grant access.

Else → show error.


5. Stop.

Program 5: Reverse a Number Using while Loop

Algorithm:

1. Start.


2. Input a number.


3. While number > 0:

Extract last digit = number % 10.

Print digit.

number = number / 10.


4. Stop.

Nested for Loop Demonstration

Algorithm:

1. Start.


2. Loop i from 1 to 2:

Loop j from 1 to 3:

Print i and j.




3. End loops.


 Pattern 1: Simple Left-Aligned Pyramid

Algorithm:

1. Start.


2. Loop i from 1 to n:

Loop j from 1 to i:

Print *.


Print newline.



3. Stop.

Pattern 2: Flipped Right-Aligned Pyramid

Algorithm:

1. Start.


2. Loop i from 1 to n:

Loop s from 1 to n - i:

Print space.


Loop j from 1 to i:

Print *.


Print newline.



3. Stop.

Pattern 3: Inverted Left-Aligned Pyramid

Algorithm:

1. Start.


2. Loop i from 1 to n:

Loop j from i to n:

Print *.


Print newline.



3. Stop.

 Pattern 4: Floyd’s Triangle – Numbers

Algorithm:

1. Start.


2. Set count = 1.


3. Loop i from 1 to n:

Loop j from 1 to i:

Print count.

Increment count.


Print newline.



4. Stop.

Pattern 5: Floyd’s Triangle – Alphabets

Algorithm:

1. Start.


2. Set ch = 'A'.


3. Loop i from 1 to n:

Loop j from 1 to i:

Print ch.

Increment ch.


Print newline.



4. Stop.

Pattern 6: Hourglass Pattern

Algorithm:

1. Start.



Top Half: 2. Loop i from n to 1:

Loop s from 1 to n - i: print space.

Loop j from 1 to 2*i - 1: print *.

Print newline.


Bottom Half: 3. Loop i from 1 to n:

Loop s from 1 to n - i: print space.

Loop j from 1 to 2*i - 1: print *.

Print newline.


4. Stop.

conclusion:

In this practical, we learned how to use loops in C++ to repeat tasks. We used the for loop when we knew how many times something should happen, and the while loop when we didn’t know the exact number of times. We wrote simple programs to print numbers, check passwords, reverse numbers, and create patterns using stars, numbers, and alphabets. Nested loops helped in printing these patterns. Loops made our code shorter, faster, and easier to understand.



