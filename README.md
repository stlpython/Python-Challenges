# Python-Challenges
Some fun practices for getting started with Python

### Challenge 1
Present a comma separated list of the numbers between four thousand and five thousand that are products of four but not products of seven.

#### Solution 
```
for item in range(4000, 5000):
    if ( item % 4 == 0 ) and ( item % 7 != 0 ):
        print(item, end = ',')
```

### Challenge 2

