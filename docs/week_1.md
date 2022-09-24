# Python Introduction I

## Python's core built-in objects

|     |     |
| --- | --- |
| Object type: | Examples: |
| *Numbers* | 123, 3.14, math.pi, ... |
| *Strings* | 'abc', 'EPFL', "Geneva", ... |
| *Lists* | [1, [2, 'troi'],4], list(range(99) |
| Dictionaries | {'Apples': 200, 'Pears': 123.5}, dict(hours=10) |
| Tuples | (x,y,z), (1, [2, 'troi'],4) |
| Sets | set('abc'), {'E','P','F','L'} |
| Other core types | Booleans, types, None |
| Files | open('data.txt'), open(r('/home/alex/abc.bin'),'wb')
| Program unit types | Functions, modules, classes |

## Strings

- strings are concatenations of letters, special characters, numbers, and spaces
- they are case sensitive!


They can be *defined* by enclosing in quotation marks (") or single quotes (').

Examples:

```python
>>> S = 'Geneva'      # make a 6-character string and assign it to a name
>>> S = "Lausanne"    # make a 8-character string and assign it to a name
>>> S = str(3)        # cast integer 3 to string and assign to name
>>> type(S)
str
```
