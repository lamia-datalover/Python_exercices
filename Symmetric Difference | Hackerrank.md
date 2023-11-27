# Here is the solution of the following exercise:
![7](https://github.com/lamia-datalover/Python_exercices/assets/145395677/560e7e19-7ad9-47cd-9f57-b273080c7480)
# Solution :
```bash
m = int(input())
set_m = set(map(int, input().split()))
n = int(input())
set_n = set(map(int, input().split()))

# Symmetric difference calculation
sym_diff = sorted(set_m.symmetric_difference(set_n))

# Outputting symmetric difference in ascending order
for num in sym_diff:
    print(num)
```
# Link to the exercise:
https://www.hackerrank.com/domains/python
