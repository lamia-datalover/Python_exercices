# Here is the solution of the following exercise:
![24](https://github.com/lamia-datalover/Python_exercices/assets/145395677/f12dda2a-badf-48eb-846d-a482021d5c88)

# Solution:
```bash
from itertools import groupby
[print((len(list(j)),int(i)),end=' ') for i,j in groupby(input())]
```
