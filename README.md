# Find_the_number
Problem
You are given a string S of length  N . The string S consists of digits from 1-9. Consider the string indexing to be 1-based.
You need to divide the string into blocks such that the ith block contains the elements from the index ((i-1)*X+1) to min(N,i*X) (both inclusive). A number is valid if it is formed by choosing exactly one digit from each block and placing the digits in the order of their block number.

For example:

If the given string is '123456789' and X=3, the blocks formed are [123], [456], [789]. Few valid numbers are 147,159,348 etc.. but 124 and 396 are invalid.

Among all the valid numbers that can be formed, your task is to determine the Kth number if all the unique valid numbers are sorted in ascending order.

Input format

First line: Three space-separated integers N,X,K and 
Second line: String  consisting of digits (1-9).
Output format

Print the  Kth valid number.
Note: Value of  will always be such that answer exists.
