# Pratikum9

## Assert Statement

```def KelvinToFahrenheit(Temperature):
assert (Temperature >= 0),"Colder than absolute zero!"
return ((Temperature-273)*1.8)+32
print KelvinToFahrenheit(273)
print int(KelvinToFahrenheit(505.78))
print KelvinToFahrenheit(-5)
```

## Exception Statement

```try:
fh = open("testfile", "r")
fh.write("This is my test file for exception handling!!")
except IOError:
print "Error: can\'t find file or read data"
else:
print "Written content in the file successfully"
```
[image1](SS/SS1.jpg)
dan ini adalah hasil ouputnya:
[image2](SS/SS2.jpg)

## Clause

```try:
fh = open("testfile", "w")
fh.write("This is my test file for exception handling!!")
finally:
print "Error: can\'t find file or read data"
```
[image3](SS/SS3.jpg)
ini adalah hasil ouputnya:
[image4](SS/SS4.jpg)

## Raise

```def functionName( level ):
if level < 1:
raise "Invalid level!", level
```
[image5](SS/SS5.jpg)
dan ini adalah hasil ouputnya:
[image6](SS/SS6.jpg)

## User Defined

```class Networkerror(RuntimeError):
def __init__(self, arg):
self.args = arg
```
[image7](SS/SS7.jpg)
dan ini adalah hasil ouputnya:
[image8](SS/SS8.jpg)




