## How to solve the following exercise of Python section:
You are asked to ensure that the first and last names of people begin with a capital letter in their passports. For example, alison heck should be capitalised correctly as Alison Heck.

Given a full name, your task is to capitalize the name appropriately.

Input Format:

A single line of input containing the full name, S .

Constraints:

0< len(S)< 27

The string consists of alphanumeric characters and spaces.

Note: in a word only the first character is capitalized. Example 12abc when capitalized remains 12abc.

Output Format:

Print the capitalized string, S.

Sample input:
```bash
  chris alan
```
Sample output:
```bash
  Chris Alan
```
## You can fin the exercise in the following link :

https://www.hackerrank.com/challenges/capitalize/problem?isFullScreen=true

## Solution of the exercise :
```bash
def solve(s):
    split_name = s.split(" ")
    
    # Capitalize the first letter of each word
    capitalized_words = [word.capitalize() for word in split_name]
    
    # Join the capitalized words back together
    capitalized_name = " ".join(capitalized_words)
    return capitalized_name

 if __name__ == '__main__':
    fptr = open(os.environ['OUTPUT_PATH'], 'w')

    s = input()

    result = solve(s)

    fptr.write(result + '\n')

    fptr.close()
```

