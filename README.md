# IceCream ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
IceCream is a simple and powerful Python library for debugging and logging. It provides tools for quickly and easily inferring variables and expressions during development, making it an ideal tool for debugging code. IceCream allows you to quickly find and fix bugs without the distraction of complex logging mechanisms.

## IceCream's main features:

- Simple syntax: IceCream provides a simple and intuitive syntax for variable and expression output.

- Automatic formatting: IceCream automatically formats the output, making it readable and understandable.

- Configurability: You can customize IceCream by specifying the level of detail, output format, and other parameters.

- Integration with other libraries: IceCream integrates easily with other Python libraries such as logging, allowing it to be used in existing projects.

- Support for multiple environments: IceCream supports output to console, files, and other environments, making it a versatile debugging tool.

## Examples of Uses:


### Variable output:
```python
from icecream import ic

# Example of variables
a = 10
b = 20

# Variable output with IceCream
ic(a, b)
```

### Expression output:
```python
from icecream import ic

# Example of an expression
result = a + b

# Expression output with IceCream
ic(result)
```

### IceCream Configuration:
```python
from icecream import ic

# Setting the level of detail
ic.configureOutput(includeContext=True)

# Output of variables with settings
ic(a, b)
```

### Using IceCream in functions:
```python 
from icecream import ic

def add(x, y):
    result = x + y
    ic(result)
    return result

# Function call
add(5, 7)
```
