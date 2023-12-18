# Here is the solution of the following exercise:
![20](https://github.com/lamia-datalover/Python_exercices/assets/145395677/615005ea-43ce-4ef0-83d0-6fcf69389cd8)

# Solution:
```bash
# Enter your code here. Read input from STDIN. Print output to STDOUT
from itertools import product

A = map(int, input().split())
B = map(int, input().split())

result = " ".join(map(str, list(product(A, B))))

print(result)

```
