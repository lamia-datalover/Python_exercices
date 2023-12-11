# Here is the solution of the following exercise:
![16](https://github.com/lamia-datalover/Python_exercices/assets/145395677/78f37723-edf9-4487-8349-b941cc4520e2)
# Solution :
```bash
T=int(input())
for _ in range(T):
    num_A=int(input())
    elem_A=set(map(int, input().split()))
    num_B=int(input())
    elem_B=set(map(int, input().split()))

    if elem_B==elem_B.union(elem_A):
        print('True')
    else:
        print('False')
```
# Link of the exercise :
https://www.hackerrank.com/challenges/py-check-subset/problem
