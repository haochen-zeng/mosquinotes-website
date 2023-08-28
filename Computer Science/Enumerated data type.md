#Definition #ComputerScience

# Definition

Data types that 

# Note

The possible values are listed in the brackets.
For example:
```
TYPE TDirections = (North, East, South, West)
```

Variables can be declared and assigned values.
For example:
```
DECALRE Direction : TDirections
Direction <- North
```

The values are ordinal. It means they can be compared to each other. This is an operation.
For example:
```
DECLARE Weekend : Boolean
DECLARE Day : TDays
Weekend = TRUE IF Day > Friday
```

The enumerated data types is one reason why user-defined data types are sometimes needed. There could not be a built-in generic definition of an enumerated data type because the possible values would not be known. The values can only be known when the programmer has identifies them in the type definition.