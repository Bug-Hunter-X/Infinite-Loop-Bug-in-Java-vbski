# Infinite Loop Bug in Java

This repository demonstrates a common error in Java programming: an infinite loop. The code provided contains a while loop that never terminates because the loop condition always evaluates to true.  The solution demonstrates how to correct the condition to ensure the loop terminates properly.

## Bug
The provided Java code contains a simple `while` loop intended to print the values of `x` from 0 to 9.  However, due to the placement of `x++`, the loop will continue indefinitely.

## Solution
The solution corrects the loop condition to ensure the loop terminates when x reaches 10.