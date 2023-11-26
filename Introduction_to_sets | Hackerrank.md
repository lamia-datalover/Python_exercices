## Here is the solution of the following exercise :
A set is an unordered collection of elements without duplicate entries.
When printed, iterated or converted into a sequence, its elements will appear in an arbitrary order.
Example:
```bash
>>> print set()
set([])

>>> print set('HackerRank')
set(['a', 'c', 'e', 'H', 'k', 'n', 'r', 'R'])

>>> print set([1,2,1,2,3,4,5,6,0,9,12,22,3])
set([0, 1, 2, 3, 4, 5, 6, 9, 12, 22])

>>> print set((1,2,3,4,5,5))
set([1, 2, 3, 4, 5])

>>> print set(set(['H','a','c','k','e','r','r','a','n','k']))
set(['a', 'c', 'r', 'e', 'H', 'k', 'n'])

>>> print set({'Hacker' : 'DOSHI', 'Rank' : 616 })
set(['Hacker', 'Rank'])

>>> print set(enumerate(['H','a','c','k','e','r','r','a','n','k']))
set([(6, 'r'), (7, 'a'), (3, 'k'), (4, 'e'), (5, 'r'), (9, 'k'), (2, 'c'), (0, 'H'), (1, 'a'), (8, 'n')])
```
Basically, sets are used for membership testing and eliminating duplicate entries.
Task:

Now, let's use our knowledge of sets and help Mickey.

Ms. Gabriel Williams is a botany professor at District College. One day, she asked her student Mickey to compute the average of 
all the plants with distinct heights in her greenhouse.

Function Description:
average has the following parameters:
int arr: an array of integers
Returns
float: the resulting float value rounded to 3 places after the decimal

Input Format:
The first line contains the integer,N , the size of arr.
The second line contains the N space-separated integers, arr[i] .
Sample Input:
```bash
STDIN                                       Function
-----                                       --------
10                                          arr[] size N = 10
161 182 161 154 176 170 167 171 170 174     arr = [161, 181, ..., 174]
```
Sample Output:
```bash
169.375
```
## Solution:
```bash
def average(array):
    # your code goes here
    the_set=set(array)
    somme=0
    for i in the_set:
        somme=somme+i
    avg=somme/len(the_set)
    return avg
    
if __name__ == '__main__':
    n = int(input())
    arr = list(map(int, input().split()))
    result = average(arr)
    print(result)
```
## Link of the exercise :
https://www.hackerrank.com/challenges/py-introduction-to-sets/problem?isFullScreen=true
