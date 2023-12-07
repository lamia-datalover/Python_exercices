# Solution of the following exercise:
![12](https://github.com/lamia-datalover/Python_exercices/assets/145395677/4ec05624-92de-4f84-b720-21bcc276f532)
# Solution :
```bash
n, set1 = int(input()), set(map(int, input().split()))
b, set2 = int(input()), set(map(int, input().split()))

total = set1.difference(set2)
print(len(total))
```
# Link of the exercise:
https://www.hackerrank.com/challenges/py-set-difference-operation/problem?isFullScreen=true
