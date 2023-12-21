# Here is the solution of the following exercise:
![45](https://github.com/lamia-datalover/Python_exercices/assets/145395677/63e92b47-547b-4895-9e43-a673ed8d051c)

# Solution:
```bash
from itertools import combinations,permutations
N=int(input())
S=input().split()
K=int(input())
count=0
comb=list(combinations(S,K))
total=len(comb)

for pair in comb:
    if('a' in pair):
        count+=1
print(count/total)
```
