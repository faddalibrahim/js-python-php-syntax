# Functions

```python


# structure of a python function
def myfunc(name):  
    print("my name is", name)

# python functions return None by default
result = myfunc("Mufti")
print(result) # None

# python function can return more than one item (tuples)
def convert_sec(secs):
    hours = secs/3600
    mins = secs/60
    return mins, hours


# unpacking(called destructuring in javascript) 
mins, hours = convert_sec(500) 
print(mins, hours)


```