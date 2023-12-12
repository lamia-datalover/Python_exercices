# Here is the solution of the following exercise:
![17](https://github.com/lamia-datalover/Python_exercices/assets/145395677/6c9a1abd-eb7d-4d9b-9cd4-aa5a3a18ebd8)
# Solution:
```bash
elem_A=set(map(int,input().split()))
n=int(input())
cpt=0
for _ in range(n):
    elem_i=set(map(int,input().split()))
    if elem_i.issubset(elem_A):
        cpt=cpt+1
        
if cpt==n:
    print("True")
else :
    print('False')          

```
# Link of the exercise:
https://www.hackerrank.com/challenges/py-check-strict-superset/problem
