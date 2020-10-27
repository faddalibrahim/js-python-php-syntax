# Data Types (including contatenation and interpolation)

dfdf

# Operators

dfdf

# Variables

dfdf

# Functions(default parameters, return value, pass by value or reference)

sdsdsd

# Loops

sdsdsds

## Javascript

*let* and *const* are *block scoped*; *var* is *function scoped*.

```javascript
let z;
z = 21;

let x = 12;

const x;   // this line will throw an error; constant variables must always be initialized

var w = 21;

x = 21;   // bad practice; this variable will be global no matter where it is declared


//  Other tricks in variable declaration

let x = y = 12;
let x = 12,
    y = 15;
```

## Python

variables are only function-scoped

```python
global z
x = '45'
y = "45"
```

## PHP

variables can be global, local or static  
variable declared outside a function is has GLOBAL scope and can only be accessed outside the function (unlike in javascript where global variables can be accessed anywhere)  

To access a global variable, use the **global** key word

```php
$x = 20

function accessGlobalX{  
   global $x;  // here, we are accessing the x that was declared outside the function
   echo $x;   // output : 20
}


define("NAME", "Michael jackson")  // declaring constant variable; automatically global
define("CARS", ["Volkswagen","Tesla","Honda"])  // constant array variable
``

___



if True:
	x = 12

print(x) ---- this line will work

if(true){
	let x = 21
}
console.log(x) --- this will not work



BOOLEAN
---javascripy---
true false

---python---
True False

# Interpolation
---javascript---
let age = 21
console.log(`I am ${age} years old`)

---python---
age = 34
print('I am {} years old'.format(age))
print(f'I am {age} years old')



name = 'Faddal'
age = 45
print('My name is {}. I am {} years old'.format(name,age))
print(f'My name is {name} I am {age} years old')

you can also use positions with the format method
print('My name is {1}. I am {0} years old'.format(name,age))
output : My name is 45. I am Faddal years old.

you can also use indentations with the format method
print('My name is {1:<9}. I am {0:>9} years old'.format(name,age))
print('My name is {1:<09}. I am {0:>09} years old'.format(name,age))
output: My name is 45       . I am    Faddal years old
output: My name is 450000000. I am 000Faddal years old
note: the length of the space is factored into the length of the argument

print(f'My name is {name>9} I am {age<9} years old')



In js, you can use template liteals for multiple lines
In python, you use tripple quotes '''my name faddal
									i am 21 years of age'''


You can use double quotes in single quoted strings and vice versa, without escaping -- both python and js


Cool List methods in python
	list.extend(other lists)
	list.copy()
	list.clear()


In python you cant add items to a list by using index, example nums =  [1,2,3,4,5]
if you want to add 6 by doing nums[5] = 6, it wont work


In javascript, you can add a new item by using index



if you wanna empty a list, you do list.clear() for python
in javascript, you do array.length = 0, or use the splice method

CONDITIONALS
---python----
has only if, no switch

---javascript---
has both


LOOPS
---python---
while and for loops, no do-while
python has for item in range()
           for item in list/tuple
           for item,index in enumerate(list)

python also has list comprehensions --  a brief option to for loops, especially if they result in a new list
Example consider this
 						multiples = []
 						for x in range(1,11):
 							multiples.append(x*7)

With list comprehensions
							multiples = [x*7 for(x in range(1,11))]

Other Examples of list comprehensions 
							languages = ['python','javascript','javascript']
							langsLength = [len(lang) for(lang in languages)]


							even = [num for num in range(1,10) if num % 2 == 0]

---javascript---
while, for and d-while loops
javascript has for(let property in array)
			   for(let item of array)


FUNCTIONS
both have default parameters

python funtions return None by default
if a python function returns multiple values, they are grouped as a tuple
tuples can be unpacked(similar to destructuring in javascript)

javascript functions return Undefined by default
if a javascript function returns multiple values, only the last one is taken

python lambda expressions are similar to one line arrow functions in javascript


CHECKING FOR DATA TYPE
---python---
type(data)

---javascript---
typeof data

falsy values in js 0,empty string, undefined, null
falsy values in py 0,empty string, None