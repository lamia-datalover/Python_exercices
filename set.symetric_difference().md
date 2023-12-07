# Here is the solution of the following exercise:
![13](https://github.com/lamia-datalover/Python_exercices/assets/145395677/93d66305-eafe-4a72-a2e4-ab2c97981592)
# Solution:
```bash
n, set1 = int(input()), set(map(int, input().split()))
b, set2 = int(input()), set(map(int, input().split()))

total = set1.symmetric_difference(set2)
print(len(total))
```
# Link of the exercise :
https://www.hackerrank.com/challenges/py-set-symmetric-difference-operation/problem?isFullScreen=tru
