# Here is the solution of the following python exercise:
![9](https://github.com/lamia-datalover/Python_exercices/assets/145395677/53b73a02-3348-4fff-82bc-0e8e8f22d6f4)
# Solution:
```bash
n=int(input())
list1=map(int,input().split())
b=int(input())
list2=map(int,input().split())
set1=set(list1)
set2=set(list2)
for i in range(n):
    total = set1.union(set2)
print(len(total))

```
# Link to the exercise:
https://www.hackerrank.com/challenges/py-set-union/problem
