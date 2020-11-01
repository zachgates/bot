Do you ever find yourself writing something like:
```py
doubled_numbers = []
for n in range(10):
    doubled_numbers.append(n * 2)
```
If we rewrite the example above to use list comprehensions, it will be more readable:
```py
doubled_numbers = [n * 2 for n in range(10)]
```
For more info, see [this article](http://www.pythonforbeginners.com/basics/list-comprehensions-in-python) or [PEP 202](https://www.python.org/dev/peps/pep-0202/).
