# Some important exercises
Question 2 - 3 - 9 - 15 - 16 - 18 - 19

## Some notes/interesting solutions

### Question 19
``` python
lis = [tuple(x.split(",")) for x in input().split(" ")]
import operator
lis.sort(key = operator.itemgetter(0,1,2))
print(lis)
```
