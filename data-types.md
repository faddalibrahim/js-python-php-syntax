# Data Types (with concatenation, interpolation and type-conversions)

All three languages have **strings**, **integers**, **floats** and **boolean**  

len(string) returns length of string in python, string.length in javascript

In javascript, integers and floats are collectively grouped under **number**   data-type

Javascript and PHP have **arrays** and **objects**  

Python has **lists**, **tuples** and **dictionaries**

**Undefined** in javascript is similar to python's **None** type

Python lists and dictionaries are similar to how arrays and objects in javascript/PHP operate

## Javascript
typeof()

parseInt
parseFloat()
 
```javascript
//concatenation

 "2" + "2" //22
 "2" + 2   //22

 //Interpolation (done with back ticks)
 let name = "Faddal",
     age = 21;
 
 print(`My name is {$name}, I am {$age} years old`) // My name is Faddal, I am 21 years old

 //type conversions
 age.toString() // converts age int to string


```

## Python
type()

when adding an int to a float, python converts the int into a float before the operation in the background. this is called implcit conversion.

variables are only function-scoped

when devision takes place between 2 integers, the output is a float

when you multiply an int and a string, the string is repeated the number of times the int...2 * "me" : "meme"

cant multiply a string and a float

to add a string to a number, you have to explicityly convert the number to a string

print("combining with a " + str(12))
we can also do print("combining with a", 12)

```python
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


```

## PHP

variables can be global, local or static  
variable declared outside a function is has GLOBAL scope and can only be accessed outside the function (unlike in javascript where global variables can be accessed anywhere)  

To access a global variable, use the **global** key word

```php
 code
```