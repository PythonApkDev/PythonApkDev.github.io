# VisageScript (Version 0.0.1)

**VisageScript** is a programming language coded in Python with a mix of Python, Java, JavaScript, 
and Ruby syntax and functionalities.

## Variable Declaration

Variables in VisageScript can be declared as either static or dynamic-typed.

### Dynamic-Typed Declaration

For dynamic-typed variable declaration, we use the keyword 'var'. In this case, it is possible to update the value 
of the variable to another type's value. The following code shows that the variable 'a' can have its type changed 
from 'int' to 'float'.

```
var a = 5;
a = 6.5;
print a
```

The code above will print the value '6.5'.

### Static-Typed Declaration

Static-typed variable declaration involves directly specifying the type of the variable declared. So far, VisageScript 
supports 'int' and 'float' types. Since both 'int' and 'float' are numeric data types, all basic arithmetic operations 
and comparison operations can be applied between them.

The following code adds an 'int' and a 'float'.

```
int a = 5;
float b = 6.5;
print a + b
```

The code above will print the value '11.5'.
