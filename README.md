# Asyncy Python

Execute a python file with arguments.

#### Example

```py
import sys
print('Hello ' + sys.argv[1] + sys.argv[2])
```
> The file above is checked into your repository at the path /print.py

```storyscript
result = python "priny.py" "foo" "bar"
```

> The variable `result` would equal `"Hello foobar"`
