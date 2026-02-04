# Python Operators

Operators are used to perform operations on variables and values in Python.
They help in calculations, comparisons, and decision making.

---

## Arithmetic Operators
Arithmetic operators are used for mathematical calculations.

| Operator | Meaning |
|--------|---------|
| + | Addition |
| - | Subtraction |
| * | Multiplication |
| / | Division |
| % | Modulus |
| // | Floor Division |
| ** | Power |

```python
a = 10
b = 3

print(a + b)
print(a - b)
print(a * b)
print(a / b)
print(a % b)

Comparison Operators

Comparison operators compare two values and return True or False.

Operator	Meaning
==	Equal to
!=	Not equal to
>	Greater than
<	Less than
>=	Greater than or equal
<=	Less than or equal
print(a // b)
print(a ** b)

x = 5
y = 10

print(x == y)
print(x != y)
print(x > y)
print(x < y)
print(x >= y)
print(x <= y)

Logical Operators

Logical operators are used to combine conditions.

Operator	Meaning
and	True if both conditions are True
or	True if any one condition is True
not	Reverse the result

age = 20

print(age > 18 and age < 25)
print(age < 18 or age > 21)
print(not(age > 18))


Assignment Operators

Assignment operators assign or update values.

Operator	Example
=	x = 10
+=	x += 5
-=	x -= 3
*=	x *= 2
/=	x /= 2

x = 10
x += 5
x -= 3
x *= 2
x /= 2

print(x)


Membership Operators

Membership operators check whether a value is present in a sequence.

Operator	Meaning
in	Value present
not in	Value not present

data = [1, 2, 3, 4]

print(2 in data)
print(5 not in data)

Identity Operators

Identity operators compare memory location of objects.

Operator	Meaning
is	Same object
is not	Different object

a = 10
b = 10

print(a is b)
print(a is not b)


