# Learning Python

**Download Python**
* https://www.python.org/downloads/

**Facts about Python**
* General purpose language
* Powerful language
* Widely used in industry
* Can be used in a great range of applications

**Examples where Python is used**  
* Web development
* Data analysis
* Machine learning
* Deep learning

**Important things about Python**  
* Python is case sensitive
* In Python, spacing is important

**Python Data Types**
* Numbers
	* Integers
	* Floats
	* Complex numbers
* Booleans
* Strings
* Lists
* Tuples
* Sets
* Dictionaries

**Operators**
* Arithmetic
* Assignment
* Comparison
* Logical

**Whitespaces**
* A block of code is denoted by increasing the identation
* The end of a block of code, is denoted by reducing the identation
* The end of a statement is marked by a newline character
	* For explicit continuation (extending many lines), the character \ can added at the end of each line
	* Multiple line continuation is implied insided (), [], and {}

**Comments**  
* Comments in Python start with a \#
* Multiple line comments:
	* either by using \# in front of each line
	* or by using triple quotes at the beggining and at the end of a comment

**Docstrings**
* Docstring stands for "Documentation String"
* It is used to describe what a certain piece of code does
* Docstrings are included in triple quotes
* It is the first statement in:
	* Functions
	* Classes
	* Modules
	* Methods

**Built-In Functions**
* print(1+2) ## 3

_Type Conversion_  
_Style Guidelines_  

**Naming Variables**
* Using only lowercase letters
* Using underscores to sepatate words

## Declaring Variables

x = 150  
y = 350  
z = x + y  
print(z)  
\#\# 500  

x = 1  
y = 2  
z = 3  
\#\# is equivalent to:  
x, y, z = 1, 2, 3  


## Arithmetic Operators

Operator | Operation
-------|-----------
 \+ | Addition
 \- | Subtraction
 \* | Multiplication
 \/ | Division
 \% | Modulo (Mod)
 \*\* | Exponentiation
 \/\/ | Division and rounding down

## Comparison Operators

 Operator | Comparison
-------|-----------
x > y | greater than
x < y | less than 
x >= y | greater than or equal to
x <= y | less than or equal to
== | equal to
!= | not equal to  


## Logical Operators

 symbol | operation
 -------|----------
 and | logical and
 or | logical or
 not | logical not

## Bitwise Operators  

symbol | operation
-------|-----------
x & y | bitwise and
x \| y | bitwise or
x ^ y | bitwise exclusive or (XOR)

## Assignment Operators

* increase x by 1
	* x = x +1
	* x += 1
* decrease y by 1
	* y = y - 1
	* y -= 1  
* multiple x by 2
	* x = x \* 2
	* x \*= 2
* divide x by 2
	* x = x / 2
	* x /= 2

## Python Lists

Lists are ordered collections of items seperated by commas.

### Defining a List  

my_first_list = [5, 8, 7, 15, 3, 10]  

my_second_list = ['five', 'eight', 'seven', 'fifteen', 'three', 'ten']  

my_third_list = [5, 'eight', 7, 'fifteen', 3, 'ten']  

### List indexing  

The indexing starts at 0, so my_first_list[0] is 5 and my_first_list[4] is 3  

There is also the option to use negative indexing, which has the advantage that we don't need to know the length of the list to access the last item.   

Negative indexing starts from the right of the list with the value of -1.    
i.e. my_first_list[-1] is 10, while my_first_list[-6] is 5.  

## Python Tuples  

Tuples are similar to lists. The are included between () and not [].  

i.e. my_first_tuple = (5, 8, 7, 15, 3, 10)  

The difference between list and tuplets is that lists are mutable while tuples are immutable, i.e. once declared, the tuples' values cannot be changed. 

## Python Sets

Sets are unordered collection of unique items included between {}, thus the indexing has no meaning in this case as the items are not ordered.    

The items though are unique and thus, any duplicate values are automatically removed.  

i.e. my_first_set = {10, 20, 10, 10, 10, 30, 20, 20, 30, 10, 20, 30}  

\>\>\> my_first_set  
\# {10, 20, 30}

## Python Dictionaries

Pyhton dictionaries are unordered collections of "key: value" pairs and are included inside {}  
i.e. my_python_dictionary = {"name": 'Merfys", species": "dog", "friends": ["Mpoumpou", "Pepita", "Gatoulis"]}  

### Accessing values

print(my_python_dictionary["name"])  
\# Output: Merfys

print(my_python_dictionary.get("name"))  
\# Output: Merfys

### Adding elements

my_python_dictionary["color"] = "brown"  
print(my_python_dictionary)   
\# Output: {"name": 'Merfys", species": "dog", "friends": ["Mpoumpou", "Pepita", "Gatoulis"], "color": "brown"}

### Changing elements

my_python_dictionary["color"] = "brown white"  
print(my_python_dictionary)   
\# Output: {"name": 'Merfys", species": "dog", "friends": ["Mpoumpou", "Pepita", "Gatoulis"], "color": "brown white"}


## Python if...else statements

**Using only if:**    

```python
if test condition:
	# code to be executed
```

**Using if...else:**  

```python
if test condition:
	# code to be executed
else:
	#code to be executed

```

**Using if...elif..else:**

```python
if test condition:
	# code to be executed
elif test condition:
	#code to be executed
else:
	#code to be executed

```

**Using multiple elif (else if) statements**:

```python
if test condition:
	# code to be executed
elif test condition:
	#code to be executed
elif test condition:
	#code to be executed
elif test condition:
	#code to be executed
else:
	#code to be executed

```

## Functions

```python
def function name(parameters):
	'''docstring explaining what 
	the function does and is included
	between triple quotes '''
	statement(s)
```
**Two types of functions**  
* Built-in functions
* User defined functions
