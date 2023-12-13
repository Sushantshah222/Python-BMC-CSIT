# Python BMC CSIT
Basics of python for BMC CSIT 7th Semester. 

## Installation
Check python version on your machine using 

``
python -- version
``
if your python version is not shown then install python

```bash
pip install python
```

Go to repo folder 
```bash
cd bmc_dharan_python
```

Firstly create new python environment using
```bash
python -m venv myenv
```
### Activate the environment

Fow Windows
```bash
myvenv\Source\activate
```

For Linux/Mac
```bash
source myvenv/bin/activate
```
### Muti line Comment

```
"""
this is multiline comment.
I can write multiple line documentation on descripition on any of my python projects.
This makes mee very easy to explain you all.
"""
```
## Variables

Variables are containers for storing data values.
Python being dynamically typed there is no command for declaring a variable.A variable is created the moment the value is assigned to it.
We can get the type of a variable using `type()` function.

Rules for python variables:
1. A variable name must start with a letter or the underscore character
2. A variable name cannot start with a number
3. A variable name can only contain alphanumeric characters and underscores (A-z, 0-9, and _ )
   
> [!IMPORTANT]
> Variable names are case-sensitive (age, Age and AGE are three different variables.)

Multiple values can be assigned to multiple variable.

```bash
x,y,z = 1,2,3
```

One value can be assigned to multiple variables.
```bash
x=y=z=5
```
## Datatypes

A data type is a classification of data which tells the compiler or interpreter how the programmer intends to use the data.
Python has the following data types built-in by default.
Text type: Str
* Numeric Type: int, float, complex
* Sequence Type: list, tuple, range 
* Mapping Type: dict
* Set Type: Set
* Boolean Type: bool
```bash
#Integer
my_integer = 10

#Float
my_float = 3.14

#String
my_string = "Hello, World!"

#Boolean
my_boolean = True

#List
my_list = [1, 2, 3, 4, 5]

#Tuple
my_tuple = (1, 2, 3, 4, 5)

#Set
my_set = {1, 2, 3, 4, 5}

#Dictionary
my_dict = {"name": "John", "age": 30, "city": "New York"}
```

## Typecasting
 Type casting is a method or process that converts a data type into another data type in both ways manually and automatically.
 
Casting in python is therefore done using constructor functions:
1. `int()` - constructs an integer number from an integer literal, a float literal (by removing all decimals), or a string literal (providing the string represents a whole number)
2. `float()` - constructs a float number from an integer literal, a float literal or a string literal (providing the string represents a float or an integer)
3. `str()` - constructs a string from a wide variety of data types, including strings, integer literals and float literals

```bash
#Typecasting from int to float
x = 5
y = float(x)
print(y)  # Output: 5.0

#Typecasting from float to int
a = 3.14
b = int(a)
print(b)  # Output: 3

#Typecasting from string to int
num_str = "10"
num_int = int(num_str)
print(num_int)  # Output: 10

#Typecasting from int to string
num_int = 20
num_str = str(num_int)
print(num_str)  # Output: "20"
```

## List

Lists are used to store multiple items in a single variable.
Properties of a list:
+ List are **ordered**.
+ List are **mutable**.
+ List allow **duplicates**.

 List:
```bash
#Example 1
my_list = ['Ram', 'Shyam','Hari', 20, 30, 40] 

#Example 2
my_list = [1, 2, 3, "four", 5.5, True, [6, 7, 8], {"nine": 9}]
```

Finding length of list using `len()`
```bash
my_list = [1, 2,"ram", 3, 4, 5, "SITA"]

list_length = len(my_list)
print(f"The length of the list is:{list_length}")

```
Acessing list item: `my_list[index number]`
```bash
my_list = [1, 2, 3, 4, 5]
my_list[2] = item
print(item)  # Output: 3
```

> [!NOTE]
> Index value starts with '0'
<img width="531" alt="python-list-index" src="https://github.com/Sushantshah222/Python-BMC-CSIT/assets/60286504/067717bd-3181-4066-8309-0e16b2d4fea0">



#### Negative Indexing:

-1 indicates last item of the list.
```bash
my_list = ['P', 'R', 'O', 'B', 'E']

print(my_list[-1])
```

#### List Slicing
```
#Slicing from index 2 to 5 
sliced_list = my_list[2:3]

print(sliced_list)  # Output: ['O']
```
```bash
my_list[1:3]                             #‘r’,’o’ # last index is excluded
my_list[:3]                              #‘p’,’r’,’o’ # if start range is empty it is by default 0
my_list[2:]                              #‘o’,’b’,’e’ # if the last index is empty it is by default the end+1
```
Add/Change items in list:
```bash
my_list[0] = ‘a’                         #replace ‘p’ with ‘a’
my_list[1:4] = [‘b’,’c’,’d’]             #replace ‘r’,’o’,’b’ with ‘b’,’c’,’d’
my_list.append(‘r’)                      # add ‘r’ to the last position of list
my_list.extend([‘a’,’b’])                #add ‘a’,’b’ to the last position
my_list.insert(1,’k’)                    # insert ‘k’ to the 2nd position
```

#### Delete list elements:
```
del my_list[2]                           # removes 3rd  element from the list
del my_list[1:5]                         # removes items from 1 to 4
```




 



