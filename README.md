# Asyncy Python

Execute a python file with arguments.

#### Example

```py
import sys
print('Hello {} {}'.format(sys.argv[1], sys.argv[2]))
```
> The file above is checked into your repository at the path /print.py

```storyscript
# Storyscript
result = python `print.py` "foo" "bar"
```

> The variable `result` would equal `"Hello foobar"`
