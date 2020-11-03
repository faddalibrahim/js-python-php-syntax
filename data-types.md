# Data Types

All three languages have strings, integers, floats and boolean  
Javascript and PHP have arrays and objects  
Python has lists and dictionaries

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

```

## PHP

variables can be global, local or static  
variable declared outside a function is has GLOBAL scope and can only be accessed outside the function (unlike in javascript where global variables can be accessed anywhere)  

To access a global variable, use the **global** key word

```php
 code
```