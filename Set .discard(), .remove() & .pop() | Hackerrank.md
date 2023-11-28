# Here is the solution of the following exercise:
![8](https://github.com/lamia-datalover/Python_exercices/assets/145395677/57dd283d-893e-4343-9b5c-843bcd86ad77)
# Solution:
```bash
n = int(input())
s = set(map(int, input().split()))
num_commands = int(input())
for _ in range(num_commands):
    command = input().split()
    if command[0] == 'pop':
        s.pop()
    elif command[0] == 'remove':
        if len(command) == 2:
            element = int(command[1])
            if element in s:
                s.remove(element)
    elif command[0] == 'discard':
        if len(command) == 2:
            element = int(command[1])
            s.discard(element)

print(sum(s))
```
# Link to the exercise:
https://www.hackerrank.com/challenges/py-set-discard-remove-pop/problem
