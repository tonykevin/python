# Python

Learning the language *Python*

## Numbers

### Features

| Operators      | Symbol | Example  | Output               |
| -------------- | ------ | -------- | -------------------- |
| Addition       | +      | `1 + 2`  | `3`                  |
| Subtraction    | -      | `10 - 3` | `7`                  |
| Multiplication | *      | `3 * 4`  | `12`                 |
| Division       | /      | `13 / 7` | `1.8571428571428572` |
| Residue        | %      | `20 % 3` | `2`                  |
| Exponents      | \*\*   | `2**8`   | `256`                |

### Functions

To solve other mathematical calculations such as: square root, round, logarithms, etc. The **math** library must be imported.

```python
import math

# Square root
math.sqrt(9)
# Round
math.ceil(1.739)
```



## Strings

### Features

It is defined using single and double quotes.

```python
'Polar bears live in "antarctica"'
"The city of 'Cusco' is majestic"
```

In a string you can include special characters(`\t`, `\n`, etc.)

> Print: function to display data in the terminal.

```python
print('Hello\nworld')
```

```bash
Hello
world
```

it can also define a string in multiple lines and include special characters with: `"""`

```python
"""
universe
	Earth
		plants	animals
"""
```

This is stored as:

```python
'\nuniverse\n\tearth\n\t\tplants\tanimals'
```

The result on the screen with `print` is:

```bash
universe
	Earth
		plants	animals
```

### Options

Can addition and multiply strings using symbols: `+` and `*`.

```python
# Addition
'Pacific' + 'ocean'
# output
'Pacific ocean'
```

```python
# Multiply
'Hi!'*3
# output
'Hi!Hi!Hi!'
```

Escape the special characters use: `\`.

```python
print('Hello\\nworld')
# output
'Hello\nworld'
```

Store the raw string it can use: `r`.

```python
print(r'\route\tasks\new')
# output
'\route\tasks\new'
```

## License

[MIT](./LICENSE)
