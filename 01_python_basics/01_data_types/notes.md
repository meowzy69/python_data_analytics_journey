
# 🐍 Python Basics - Data Types

## 📖 What are Data Types?

A data type tells Python what kind of value is being stored in a variable.

---

# Basic Data Types

## 1. Integer (int)

- Stores whole numbers.
- No decimal point.

Example:

```python
age = 23
```

---

## 2. Float (float)

- Stores decimal numbers.

Example:

```python
salary = 45500.75
```

---

## 3. String (str)

- Stores text.
- Must be enclosed inside single (' ') or double (" ") quotes.

Example:

```python
city = "Bhopal"
```

---

## 4. Boolean (bool)

- Stores only two values:
  - True
  - False

Example:

```python
is_active = True
```

---

# Variables

A variable is a named container that stores a value.

Example:

```python
name = "Chandrapal"
```

Variable Name → name

Stored Value → "Chandrapal"

---

# Assignment Operator (=)

The "=" symbol is called the Assignment Operator.

It assigns (stores) a value inside a variable.

Example:

```python
age = 23
```

Read it as:

"Assign 23 to the variable age."

Do NOT read it as:

"Age equals 23."

---

# print()

Purpose:

Displays output on the screen.

Example:

```python
print(name)
```

Output:

```
Chandrapal
```

---

# type()

Purpose:

Checks the datatype of a variable.

Example:

```python
print(type(age))
```

Output:

```
<class 'int'>
```

---

# input()

Purpose:

Accepts input from the user.

Example:

```python
name = input("Enter your name: ")
```

Important:

✅ input() ALWAYS returns a string.

Even if the user enters:

```
23
```

Python stores:

```python
"23"
```

NOT

```python
23
```

---

# Type Casting

Type Casting means converting one datatype into another.

Examples:

```python
int()
float()
str()
bool()
```

Example:

```python
age = int(input("Enter age: "))
```

---

# Temporary vs Permanent Conversion

Temporary Conversion

```python
number = "50"

print(int(number))
```

number is STILL a string.

Permanent Conversion

```python
number = "50"

number = int(number)
```

Now number becomes an integer.

---

# Common Beginner Mistakes

❌ Adding string and integer

```python
"20" + 5
```

Results in:

TypeError

Correct:

```python
int("20") + 5
```

---

❌ Forgetting type casting

Wrong:

```python
age = input()

print(age + 5)
```

Correct:

```python
age = int(input())

print(age + 5)
```

---

# Interview Questions (Fresher)

### Q1. What is a variable?

A variable is a named container used to store data.

---

### Q2. What are Python's basic data types?

- int
- float
- str
- bool

---

### Q3. What is the difference between int and float?

int stores whole numbers.

float stores decimal numbers.

---

### Q4. What does input() return?

input() always returns a string.

---

### Q5. Why do we use type()?

To check the datatype of a variable.

---

### Q6. Why do we use print()?

To display output on the screen.

---

### Q7. What is type casting?

Converting one datatype into another.

Example:

```python
int("25")
```

---

### Q8. Difference between

```python
int(age)
```

and

```python
age = int(age)
```

int(age)

→ Temporary conversion

age = int(age)

→ Permanent conversion because the converted value is assigned back to the variable.

---

# Data Analytics Connection

Understanding data types is essential because datasets contain different kinds of information.

Example:

| Dataset Column | Data Type |
| -------------- | --------- |
| Customer Name  | str       |
| Age            | int       |
| Salary         | float     |
| Purchased      | bool      |

Before analyzing data in Pandas, a Data Analyst always checks data types.

---

# Golden Rules

✅ Variables store values.

✅ input() always returns a string.

✅ print() displays output.

✅ type() checks datatype.

✅ Use int(), float(), str() to convert data types.

✅ Use meaningful variable names.

✅ Use snake_case for variable names.

Example:

```python
customer_name
product_price
purchase_amount
```

---

# Module Summary

After completing this module, I can:

✔ Create variables

✔ Identify data types

✔ Use print()

✔ Use type()

✔ Take user input

✔ Perform type casting

✔ Explain temporary vs permanent conversion

✔ Solve beginner Python programs involving data types
