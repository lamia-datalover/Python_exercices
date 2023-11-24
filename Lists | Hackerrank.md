## Here is the solution of the following exercise:
![5](https://github.com/lamia-datalover/Python_exercices/assets/145395677/5e269ac0-0001-4932-ba7d-8088907ffded)
## Solution:
```bash
if __name__ == '__main__':
    N = int(input())
    arr = []
    for j in range(N):
        func = (input().split())
        if func[0] == "insert":
            arr.insert(int(func[1]),int(func[2]))
        elif func[0] == "print":
            print(arr)
        elif func[0] == "remove":
            arr.remove(int(func[1]))
        elif func[0] == "append":
            arr.append(int(func[1]))
        elif func[0] == "sort":
            arr.sort()
        elif func[0] == "pop":
            arr.pop()
        elif func[0] == "reverse":
            arr.reverse()
```
## Link of the exercise:
https://www.hackerrank.com/challenges/python-lists/problem
