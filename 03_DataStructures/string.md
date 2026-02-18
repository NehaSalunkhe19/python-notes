Definition

A string is a sequence of characters enclosed in quotes (' ' or " ").
In Python, strings are immutable (cannot be changed after creation).

🧱 Creation of Strings
s1 = "Hello"
s2 = 'Python'
s3 = """This is
a multiline
string"""

⚙️ String Operations
1. Traversal
s = "Python"
for ch in s:
    print(ch)

2. Indexing
s = "Python"
print(s[0])   # P
print(s[-1])  # n

3. Slicing
s = "Programming"
print(s[0:6])   # Progra
print(s[3:])    # gramming
print(s[:5])    # Progr

🛠 Common String Functions
s = "  Hello Python  "

print(len(s))            # length
print(s.upper())         # uppercase
print(s.lower())         # lowercase
print(s.strip())         # remove spaces
print(s.replace("Python","World"))
print(s.split(" "))      noting

🔁 String Concatenation
a = "Hello"
b = "World"
c = a + " " + b
print(c)

🔍 Searching in String
s = "Python Programming"

if "Python" in s:
    print("Found")
else:
    print("Not Found")
