# Here is the solution if the following exercise:
![21](https://github.com/lamia-datalover/Python_exercices/assets/145395677/80807c4c-4db0-40b1-bcd6-c16c4df3ba5f)

# Solution:
```bash
# Enter your code here. Read input from STDIN. Print output to STDOUT
from itertools import combinations_with_replacement
s, k = input().split()
k = int(k)
c = sorted(s)
for x in combinations_with_replacement(c, k):
    print(''.join(x))
```
