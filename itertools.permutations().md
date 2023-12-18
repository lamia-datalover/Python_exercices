# Here is the solution of the following exercise:
![18](https://github.com/lamia-datalover/Python_exercices/assets/145395677/40befb00-c6f0-4388-8707-358ac66f70a5)
# Solution:
```bash
# Enter your code here. Read input from STDIN. Print output to STDOUT
from itertools import permutations

# Reading the input
input_string, r = input().split()
r = int(r)

# Generating and sorting the permutations
perm_list = list(permutations(input_string, r))
perm_list.sort()

# Printing the permutations
for perm in perm_list:
    print(''.join(perm))
```
