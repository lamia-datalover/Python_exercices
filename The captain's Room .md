# Here is the solution of this exercise:
![15](https://github.com/lamia-datalover/Python_exercices/assets/145395677/b1535446-ee3c-4587-b767-9e1599b886cc)
# Solution:
```bash
if __name__ == '__main__':
    k = int(input())
    rooms = list(map(int, input().split()))
    room_set = set(rooms)  # unique room numbers
    print((sum(room_set) * k - sum(rooms)) // (k - 1))
```
