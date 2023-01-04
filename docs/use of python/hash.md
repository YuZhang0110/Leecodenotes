# hash

## define, insert and lookup




 code below define a hashtable

 `hashmap = {}`

 we can try insert element in it.

 `hashmap[1] = 0`

 "**Notice in python if the key is not exist, there will be an error**"

Always use these way to travel a hash map:

```
n = 3
for i in range(n):
	if i in hashmap:
		print(True)
```