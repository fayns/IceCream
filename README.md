# IceCream
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

# Пример переменных
a = 10
b = 20

# Вывод переменных с помощью IceCream
ic(a, b)
```
