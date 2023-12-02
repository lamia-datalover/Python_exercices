# Here is the solution of this exercise:
![10](https://github.com/lamia-datalover/Python_exercices/assets/145395677/41bec7e7-43ff-4b97-90a7-0521e7230cb2)
 # Solution:
 ```bash
# Enter your code here. Read input from STDIN. Print output to STDOUT
eng = int(input())
eng1 = set(map(int, input().split()))
frn = int(input())
frn2 = set(map(int, input().split()))
total = eng1.intersection(frn2)
print(len(total))
```
# Link of the exercise:
https://www.hackerrank.com/challenges/py-set-intersection-operation/problem
