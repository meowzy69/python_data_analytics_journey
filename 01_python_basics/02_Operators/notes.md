
# Module 2 - Operators Notes

## Arithmetic Operators

Used to perform mathematical calculations.

| Operator | Description    | Example |
| -------- | -------------- | ------- |
| +        | Addition       | 5 + 3   |
| -        | Subtraction    | 5 - 3   |
| *        | Multiplication | 5 * 3   |
| /        | Division       | 5 / 3   |
| //       | Floor Division | 5 // 3  |
| %        | Modulus        | 5 % 3   |
| **       | Exponent       | 5 ** 3  |

---

## Comparison Operators

Used to compare values and return a Boolean result.

| Operator | Description              |
| -------- | ------------------------ |
| ==       | Equal to                 |
| !=       | Not equal to             |
| >        | Greater than             |
| <        | Less than                |
| >=       | Greater than or equal to |
| <=       | Less than or equal to    |

---

## Logical Operators

Combine multiple conditions.

| Operator | Description                                    |
| -------- | ---------------------------------------------- |
| and      | Returns True if both conditions are True       |
| or       | Returns True if at least one condition is True |
| not      | Reverses the Boolean value                     |

---

## Assignment Operators

Used to update variable values.

Examples:

```python
x += 5
x -= 5
x *= 5
x /= 5
```

---

## Membership Operators

Used to check whether a value exists inside a sequence.

```python
"Python" in skills

"Java" not in skills
```

---

## Identity Operators

Used to compare whether two variables refer to the same object.

```python
a = [1,2]
b = [1,2]
c = a

a == b      # True

a is b      # False

a is c      # True
```

---

## Important Notes

- Use `==` to compare values.
- Use `is` to compare object identity.
- Use `in` only to check membership.
- Use meaningful variable names.
- Use assignment operators whenever appropriate.

---

## Interview Tips

Difference between `==` and `is`

- `==` compares values.
- `is` compares memory objects.

Example:

```python
list1 = [1,2]
list2 = [1,2]

list1 == list2      # True
list1 is list2      # False
```
