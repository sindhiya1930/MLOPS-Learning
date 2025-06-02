
# Variables

- Python has no command for declaring a variable.
- A variable is created the moment you first assign a value to it.
- Variables do not need to be declared with any particular type, and can even change type after they have been set.
>  x = 4       # x is of type int
>  x = "Sally" # x is now of type str
>  print(x)
- specify the data type of a variable, this can be done with casting
> x = str(3)
> print(type(x)) : get the type
- variables can be declared either by using single or double quotes:
- Variable names are case-sensitive.
- Variable Name
  - case sensitive
  - start with letter or _
  - A-z 0-9 _
  - Pascal case, Camel Case, Snake case
- Multiple variable
> x,y,z = "Orange","Mango","Apple"
> x=y=z="Orange"
> fruits = ["Orange", "Apple", "Banana"]
>   x,y,z=fruits

**Datatypes**
- int
- float
- complex
- str
- bool
- list
- set
- tuple
- dict
- frozenset
  
**Random values**
> import random
> print(random.randrange(1, 10))

**Strings**
double or single
x[3]
len(x)
x in "banana"
x not in "banana"
for i in "banana"
x[2:5](f:l-1), x[:5], x[2:]
a.upper()
a.lower()
a.strip()
a.replace("H","j")
a.split(",")
a+b
a+""+b
Create an f-string:
  age = 36
  txt = f"My name is John, I am {age}" 
  
- List is a collection which is ordered and changeable. Allows duplicate members.
    - insert, append, extend, remove, pop, del
    - newlist = [expression for item in iterable if condition == True]
- Tuple is a collection which is ordered and unchangeable. Allows duplicate members.
- Set is a collection which is unordered, unchangeable*, and unindexed. No duplicate members.
- Dictionary is a collection which is ordered** and changeable. No duplicate members.

 

    
