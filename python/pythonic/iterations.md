### Pythonic way to do nested iteration
```
# non pythonic
x = [1, 2, 3]
y = [4, 5, 6]

output = []
for outer in x:
    for inner in y:
        output.append(outer + inner)
print(output)

```

```
# pythonic
x = [1, 2, 3]
y = [4, 5, 6]

print([inner + outer for outer in x for inner in y])

```