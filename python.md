# Python

## Definitions

`variables`: Variables are containers for storing data values.
```
x = 5
y = "John"
print(x)
print(y)`
```
`assigment` In Python, variables are created when you assign a value to it.

`Literals``
Literal is a raw data given in a variable or constant. In Python, there are various types of literals they are as follows:

* Numeric Literals
integer, float, complex

```python
a = 3 # integer
a = 4.2 # float
x = 3.14j # complex literal
```

* String Literals
A string literal is a sequence of characters surrounded by quotes

```python
"Hello world"
```

* Boolean Literals
A Boolean literal can only have one of this two values True or False

```python
x = (1 == True)
y = (1 == False)
a = True + 4
b = False + 10
```



`variables name`

* A variable name must start with a letter or the underscore character
* A variable name cannot start with a number
* A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
* Variable names are case-sensitive (age, Age and AGE are three different variables)

```python
#Legal variable names:
myvar = "John"
my_var = "John"
_my_var = "John"
myVar = "John"
MYVAR = "John"
myvar2 = "John"

#Illegal variable names:
2myvar = "John"
my-var = "John"
my var = "John"
```

`scope` 

A variable created inside a function belongs to the local scope of that function, and can only be used inside that function.
```
def myfunc():
  x = 300
  print(x)

myfunc()
````
`output variables`
 
``print statement`` is often used to output variables.

```python
x = "Python is "
y = "awesome"
z =  x + y
print(z)
```
`concatenation`

One common task you’ll need to accomplish with any language involves merging or combining strings. This process is referred to as concatenation.

* concatenation of strings:

```

```

`expression` 

Expressions are representations of value. They are different from statement in the fact that statements do something while expressions are representation of value. For example any string is also an expressions since it represents the value of the string as well.


```python
"Hello world" 
2+1

```

`statement`

Instructions that a Python interpreter can execute are called statements.

```python
a = 3
if
for 
while
```
