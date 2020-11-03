# Data Types (with concatenation, interpolation and type-conversions)

All three languages have **strings**, **integers**, **floats** and **boolean**  

In javascript, integers and floats are collectively grouped under **number**   data-type

Javascript and PHP have **arrays** and **objects**  
Python has **lists** and **dictionaries**

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

```

## PHP

variables can be global, local or static  
variable declared outside a function is has GLOBAL scope and can only be accessed outside the function (unlike in javascript where global variables can be accessed anywhere)  

To access a global variable, use the **global** key word

```php
 code
```