## Given-a-nested-list-extend-it-with-adding-sub-list-h-i-j-in-a-such-a-way-that-it-will-look
## Nest List extended with adding sub list 
```sh
list1 = ["a", "b", ["c", ["d", "e", ["f", "g"], "k"], "l"], "m", "n"]
subList = ["h", "i", "j"]

list1[2][1][2].extend(subList)
print(list1)
```
## Example Output
['a', 'b', ['c', ['d', 'e', ['f', 'g', 'h', 'i', 'j'], 'k'], 'l'], 'm', 'n']
