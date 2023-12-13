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




