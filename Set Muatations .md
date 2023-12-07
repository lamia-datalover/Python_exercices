# Here is the solution of the following exercise:
![14](https://github.com/lamia-datalover/Python_exercices/assets/145395677/cee9109c-a094-47ed-bd51-e2ecc1da9547)
# Solution:
```bash
num_elem_A = int(input())
setA = set(map(int, input().split()))

N_other_set = int(input())

for _ in range(N_other_set):
    operation,_ = input().split()
    helping_line = set(map(int, input().split()))
    
    if operation == 'update':
        setA.update(helping_line)
    elif operation == 'symmetric_difference_update':
        setA.symmetric_difference_update(helping_line)
    elif operation == 'intersection_update':
        setA.intersection_update(helping_line)
    else:
        setA.difference_update(helping_line)

print(sum(setA))
```
# Link of the exercise:
https://www.hackerrank.com/challenges/py-set-mutations/problem?isFullScreen=true
