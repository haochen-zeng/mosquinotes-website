#Definition #ComputerScience 

# Definition

A [[data type]] which the value is the address in memory of a different variable.

# Notes

`^` before a [[data type]] is used for definition.
For example:
```
TYPE 
TIntegerPointer = ^Integer
```

Declaration which does not require the use of the `^`.
For example:
```
DECALRE MyIntegerPointer : TIntegerPointer
```

`@` is used to get the address of a variable.
`^` after an [[pointer variable]] means the values stored at the memory location specified by the [[pointer variable]].
For example:
```
DECLARE MyIntegerPointer : TIntegerPointer
DECLARE Number1, Number2 : INTEGER
Number1 <- 100
MyIntegerPointer <- @Number1
Number2 <- MyIntegerPointer^ * 2
```

Not all programming languages offer support it.
Those languages that do so will have their own version of the symbolism illustrated above with `^` and `@`.

Advanced topic:
Because arithmetic can be performed on [[pointer variable]], it is possible to use [[pointer variable]] to construct dynamically varying data structure.
For some programming languages it is necessary to declare an array with a large upper bound to ensure that the array is unlikely to be fully populated with values.
If the language supports the use of a [[pointer variable]], the size of an array can expand while a program is running.
The details of how this can be done are beyond the scope of this discussion.