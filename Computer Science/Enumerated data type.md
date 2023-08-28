#Definition #ComputerScience

# Definition

A non-composite [[user-defined data type]] for which the definition identifies all possible values.

# Notes

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

The values are [[ordinal]].
For example:
```
DECLARE Weekend : Boolean
DECLARE Day : TDays
Weekend = TRUE IF Day > Friday
```

One example of [[user-defined data type]]. 
There could not be a built-in generic definition because the possible values would not be known.
The values can only be known when the programmer has identified them in the type definition.