# Some important exercises
Question 2 - 3 - 9 - 15 - 16 - 18 - 19 - 22

## Some notes/interesting solutions

### Question 19
``` python
lis = [tuple(x.split(",")) for x in input().split(" ")]
import operator
lis.sort(key = operator.itemgetter(0,1,2))
print(lis)
```
### Question 22
```python
import operator
word= input().split(" ")
word_uni = set(word)
dic = {}
for i in word_uni:
    dic[i] = word.count(i)
dic_sorted = dict(sorted(dic.items(), key = operator.itemgetter(0)))
print(dic_sorted)
```
