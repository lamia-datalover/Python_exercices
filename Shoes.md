# Here is the solution of the following exercise:
![26](https://github.com/lamia-datalover/Python_exercices/assets/145395677/a8362f8a-bc8f-46f4-9283-f4ba469115fe)

# Solution:
```bash
# Enter your code here. Read input from STDIN. Print output to STDOUT
shoe_number = int(input())
shoe_size = list((input().split()))
customer_number = int(input())
total_price = []
for i in range(customer_number):
    desired = list(input().split())
    if desired[0] in shoe_size:
      shoe_size.pop(shoe_size.index(desired[0]))
      price = desired[1]
      total_price.append(int(price))
print(sum(total_price))

```
