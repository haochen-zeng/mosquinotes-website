#Definition #ComputerScience 

# Definition

The value is a reference to a memory location.

# Note

For example:
```
TYPE 
TIntegerPointer = ^Integer
```
The caret is used.
A variable of TIntegerPointer stores a memory address of an Integer variable.

For example:
```
DECLARE MyIntegerPointer : TIntegerPointer
DECLARE Number1, Number2 : INTEGER
Number1 <- 100
MyIntegerPointer <- @Number1
Number2 <- MyIntegerPointer^ * 2
```
@ is used to get the address of a variable
^ after an pointer means the values stored at the memory location specified by the pointer
^ before a data type is used to define a pointer

Not all programming languages offer support for the use of a pointer data type. Those languages that do so will have their own version of the symbolism illustrated above with ^ and @.
Advanced topic:
Because arithmetic can be performed on pointer variables, it is possible to use pointer variables to construct dynamically varying data structures. For some programming languages it is necessary to declare an array with a large upper bound to ensure that the array is unlikely to be fully populated with values. If the language supports the use of a pointer variable, the size of an array can expand while a program is running. The details of how this can be done are beyond the scope of this discussion.