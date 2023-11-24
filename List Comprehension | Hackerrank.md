## Here is the solution of the following Python exercise:
![1](https://github.com/lamia-datalover/Python_exercices/assets/145395677/18124fcc-497d-4ff3-8a55-8f04e86eb031)
Sample output:
```bash
1
1
1
2
```
Sample output:
```bash
[[0, 0, 0], [0, 0, 1], [0, 1, 0], [1, 0, 0], [1, 1, 1]]
```
![1prime](https://github.com/lamia-datalover/Python_exercices/assets/145395677/42dc3359-38c4-429f-80e8-a66d91cd440b)

Sample output 1
```bash
2
2
2
2
```
Sample output 1
```bash
[[0, 0, 0], [0, 0, 1], [0, 1, 0], [0, 1, 2], [0, 2, 1], [0, 2, 2], [1, 0, 0], [1, 0, 2], [1, 1, 1],
[1, 1, 2], [1, 2, 0], [1, 2, 1], [1, 2, 2],[2, 0, 1], [2, 0, 2], [2, 1, 0], [2, 1, 1], [2, 1, 2], [2, 2, 0], [2, 2, 1], [2, 2, 2]]
```
## Solution of the exercise :
```bash
if __name__ == '__main__':
    x = int(input())
    y = int(input())
    z = int(input())
    n = int(input())
    
x = [*range(x+1)]

y = [*range(y+1)]

z = [*range(z+1)]

res = [[i,j,k] for i in x for j in y for k in z if i+j+k != n]

print(res)
```
