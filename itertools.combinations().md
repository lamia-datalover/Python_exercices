# Here is the solution of this exercise:
![19](https://github.com/lamia-datalover/Python_exercices/assets/145395677/f59e0bd5-9b3d-46da-819f-9275579213b5)

# Solution:
```bash
from itertools import combinations
string, k = list(input().split())
for i in range(1, int(k)+1):
    for y in list(combinations(sorted(string), i)):
        print(''.join(y))
```
