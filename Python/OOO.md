# Class/ Object

> class MyClass:
>   x = 5

> p1 = MyClass()
> print(p1.x)

Functions
__init__(self, initial fucntion which initialises the class objects
__str__(self,  returns string of class object since normal objets cant be printed
def myfunctiion(self) -> function inside classself is the first param to be used

example
class Person:
  def __init__(self, name, age):
    self.name=name
    self.age=age
  def __str__(self):
    return f"{self.name}({self.age})"
  def myfunc(self):
    print("Hello function")
p1=Person("John", 36)
print(p1.age)
print(p1.name)
print(p1)
print(p1.myfunc())

JSON Parse
import json
JSON -> Python dict json.loads
Python -> Json json.dumps
indent json.dumps(x,indent=4)
sort json.dumps(x,sort_keys=True)

pip package manager
pip install (installs all packages)


Virtual env
python -m venv myfirstproject

myfirstproject
  Include
  Lib
  Scripts
  .gitignore
  pyvenv.cfg

myfirstproject\Scripts\activate

delete: rmdir /s /q myfirstproject
