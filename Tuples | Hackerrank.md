## Here is the solution of the following exercise :
![6](https://github.com/lamia-datalover/Python_exercices/assets/145395677/8267d2ab-e9d1-4d8b-a296-55dade61225e)
## Solution :
```bash
if __name__ == '__main__':
    import hashlib
    n = int(input())
    integer_list = map(int, input().split())
    t= tuple(integer_list)
    res=hash(t)
    print(res)       

```
## The link of this exercise:
https://www.hackerrank.com/challenges/python-tuples/problem?isFullScreen=true
