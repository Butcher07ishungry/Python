# Python Basics  

---

## **What is a Variable?**  
A **variable** is like a container that stores data in memory.  
When you assign a value to a variable, the computer reserves some space in its memory and keeps the value there.  

In Python, creating a variable is simple:  

```python
variable_name = value
x = 5
Here, x is the variable name, and 5 is the value stored inside it.

Rules for Naming a Variable
While naming a variable, you must follow these rules:

Must start with an alphabet or underscore (_)

Can contain only letters, digits, and underscores

Cannot use reserved keywords (e.g., for, if, while, class, etc.)

Spaces are not allowed

Variables are case-sensitive (name and Name are different)

✅ Examples:

python
Copy code
age = 21
_name = "Ammar"
user123 = "Python"
❌ Invalid examples:

python
Copy code
2name = "wrong"      # starts with digit
user name = "wrong"  # contains space
class = "wrong"      # reserved keyword
How to Print a Variable?
Printing a variable is not the same as printing normal text.

If you just want the value:

python
Copy code
var = 23
print(var)   # Output: 23
If you want the value inside " " (quotes):

python
Copy code
print(f'"{var}"')   # Output: "23"
If you want text + variable together:

python
Copy code
name = "Ammar"
print(f"Hello {name}, welcome!")   # Output: Hello Ammar, welcome!
Data Types in Python
Python has different kinds of data types:

Numbers → int, float, complex

Text → str

Sequences → list, tuple, range

Mapping → dict

Sets → set, frozenset

Boolean → bool (True / False)

Binary → bytes, bytearray, memoryview

Special → NoneType (represents nothing)

✅ Examples:

python
Copy code
num = 10             # int
pi = 3.14            # float
z = 2 + 3j           # complex

text = "Python"      # str

my_list = [1, 2, 3]  # list
my_tuple = (1, 2, 3) # tuple
my_range = range(5)  # range

person = {"name": "Ali", "age": 22}  # dict

my_set = {1, 2, 3}   # set
frozen = frozenset([1, 2, 3]) # frozenset

flag = True          # bool
data = b"Hello"      # bytes

nothing = None       # NoneType
How Input and Output Functions Work
Printing Output
Print a simple line:

python
Copy code
print("That line")
Print a variable:

python
Copy code
name = "Ammar"
print(name)
Print text + variable:

python
Copy code
print(f"Hello {name}, you are learning Python!")
Taking Input
By default, the input() function always takes input as a string.

Simple input:

python
Copy code
user_name = input("Enter your name: ")
print(f"Hello {user_name}")
Input with specific data type:

python
Copy code
age = int(input("Enter your age: "))   # converts input to integer
height = float(input("Enter your height: "))  # converts to float
✅ End of Notes
yaml
Copy code

---

✨ This way, your GitHub README will look **clean, well-structured, and beginner-friendly**.  

Do you want me to also **add a small "Practice Section" at the end** (like exercises for the reader: declare a variable, print it, take input, etc.)? That would make it even more engaging.







Ask ChatGPT
