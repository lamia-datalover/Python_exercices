## Here is the solution of this python exercise:
![4](https://github.com/lamia-datalover/Python_exercices/assets/145395677/a9d2ed65-2501-40c8-80d6-52d2f8a619f5)
## Solution:
```bash
if __name__ == '__main__':
    n = int(input())
    student_marks = {}
    for _ in range(n):
        name, *line = input().split()
        scores = list(map(float, line))
        student_marks[name] = scores
    query_name = input()
    
if query_name in student_marks:
    average = sum(student_marks[query_name])/len(student_marks[query_name])
print(f'{average:.2f}'
```
## The exercise can be found here:
https://www.hackerrank.com/challenges/finding-the-percentage/problem
