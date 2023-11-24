## Here is the solution of the following exercise:
![3](https://github.com/lamia-datalover/Python_exercices/assets/145395677/96799c86-7a7b-4bb9-aade-7eb11d910e01)
## Solution:
```bash
   results =[]
   scores = []
    for _ in range(int(input())):
        name = input()
        score = float(input())
        results.append([name,score])
        scores.append(score)
        
    second_score = sorted(set(scores))[1]
    
    for a,c in sorted(results) :
        if c == second_score :
            print(a)
    
```
## This exercise can be found in the following link:
https://www.hackerrank.com/challenges/nested-list/problem?isFullScreen=true
