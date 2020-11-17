# Data Types  

## Javascript  

javascript groups floats and integers under the **Number** data type  
**back ticks** can be used to write **multiline** strings, in python, we use **tripple quotes**

```javascript
String
Number -- Infinity, NaN
null
undefined (similar to None in python)
Boolean
Object -- Array

//checking data type

typeof "i am a string" //string
typeof 24             //number

//concatenation

 "2" + "2" //22
 "2" + 2   //22

//Interpolation  

 let name = "Faddal",
     age = 21;

 print(`Name : {$name}; Age : {$age}`) // Name : Faddal; Age : 21

 //type conversions

 age.toString() // converts age int to string
 age + ""      // adding a number to a string concatenates them

 let string_age = "21"
 +string_age //converts it to a number, if its invalid, NaN
 parseInt(string_age)
 parseFloat(string_age)

 toFixed -- decimal places
 toPrecision -- significant figures
 toExponential -- 


```

## Python
type()

when adding an int to a float, python converts the int into a float before the operation in the background. this is called implcit conversion.

variables are only function-scoped




we can also do 

```python
integer -- int
float -- float
string -- str

list
dictionary -- dict
tuple
Set

None -- NoneType

# checking data type
type("string here") # <class 'str'>

# concatenation
print("combining with a " + str(12))
print("combining with a", 12)

# interpolation / Formatting

#Strings
name = "Faddal"
print(name[0])

# negative indexing to access items in a strings
name[-1] #l

# slicing a string
name[1:4] # add
name[:4] # Fadd
name[3:] # dal

#some methods
name.index("F") #returns index of the letter
name.strip()
name.count("a") #count occrrences of a substring or letter
name.endsWith("al")
name.isnumeric("1234")
name.isalpha("df")
"".join(["a","b","c"])
"this is a string".split()
string.replace(old, new)

# if you try to access a non-exisitng value in a string, it throws a value error
name.index("z") # value error here

#check if a substring is present in a string
"ad" in name # true

# formatting strings
"Hello my name is {}. I am {} years".format(name,age)
"Hello my name is {name}. I am {age} years".format(name="Blah Blah",age="67")
"Price: ${:.2f} Tax : ${:.2f}".format(7.5,8.175) #Price : $7.50 Tax : $8.18
"{:>3} F {:>3.2f}"
'{:d}'.format(10.5) → '10'
'{:.2s}'.format('Python') → 'Py'
'{:<6s}'.format('Py') → 'Py    '
'{:>6s}'.format('Py') → '    Py'
'{:^6s}'.format('Py') → '  Py ' # string centered in that many spaces

first = "apple"
second = "banana"
third = "carrot"

"{0} {2} {1}".format(first, second, third)

"""Outputs:
apple carrot banana
"""


>>> name = "Micah"

>>> print(f'Hello {name}')

Hello Micaah


# LISTS
.append()
.insert(index, item-to-add)
.remove("melon")
.pop(index)
.extend(other lists)
concatenate lists with +

for i in range()
for item in items
for index,item in enumerate(list) # returns a tuple of the index and item

#DICTIONARIES

You can use [numbers, booleans, strings, tuples] data type as key in python dictionaries

del dictt[key] #deletes an item from dictionary
use in to check if a key exists

if you loop through a dictionary, you are looping through the keys

if you wanna return both, 
for key,value in dictt.items()

dictt.keys()
dictt.values()

dictt.clear()

dict.update(other_dictt) #Updates the dictionary with the items coming from the other dictionary. Existing entries will be replaced; new entries will be added.


```

## PHP

variables can be global, local or static  
variable declared outside a function is has GLOBAL scope and can only be accessed outside the function (unlike in javascript where global variables can be accessed anywhere)  

To access a global variable, use the **global** key word

```php
 code
```