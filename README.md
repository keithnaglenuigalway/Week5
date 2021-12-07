## Week 4

### You are required to complete the following two programming questions:
### Question 1
Define a function called hypotenuse that calculates the length of the hypotenuse of a right triangle when the other two sides are given. Use this function in a program to determine the length of the hypotenuse for each of the following triangles. The function should take two arguments of type double and return the hypotenuse as a double. Test your program with the side values specified below:

|Triangle|Side 1|Side 2|
| ------ |:----:| ----:|
|1|3.0|4.0|
|2|5.0|12.0|
|3|8.0|15.0|

[20 Marks]
### Question 2
The factorial of a nonnegative integer n, written as n!, is a mathematical calculation that is the product of all positive integers less than or equal to n.  The calculation of factorials is one example of the use of recursion. The calculation can be written as:

n! = n * (n-1) * (n-2) * … 1

where 1! = 1, and 0! is defined to be 1 as well.

e.g. 5! = 5 * (5-1) * (5-2) * (5-3) * (5-4) or 5 * 4 * 3 * 2 * 1 = 120

In this exercise, you will be using factorials to calculate a mathematical series.

Perform the following steps for this exercise:

1.  One of the tenets of modern Software Engineering is code reuse. There are many instances of functions that implement the factorial schema on the Internet.  Locate a recursive instance, then code and test it. (5 marks)

2.  Use the factorial function to calculate the series:

e = 1/0! + 1/1! + 1/2! + 1/3! + … for 20 terms.                                            (20 marks)
               
3.  Write the same series calculation (as in part 2) using an iterative loop of your choice. (20 marks)

4.  Using suitable loops, repeat each function 10,000 times (i.e. calculate the same series 10,000 times for the recursive approach and 10,000 times for the iterative approach). (5 marks)

5.  Add code to measure the time it takes for the recursive and iterative loop methods to calculate the first 20 terms of the series 10,000 times.
Present your timing results. (20 marks)

6.  Based on your timing results, comment on the quote: “Would any of you very experienced programmers, if asked to code an iterative loop (like a mathematical series), think of using recursion or would that be a ‘mistake’ that a rookie programmer would leap to?” (10 marks)

[80 Marks]
