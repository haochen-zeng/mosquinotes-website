---
date: 2023-08-29
draft: false
tags:
  - Definition
  - Computer science 
---

# Definition

A non-composite [[User-defined data type]] for which the definition identifies all possible values.

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

The values are [[Ordinal]].
For example:
```
DECLARE Weekend : Boolean
DECLARE Day : TDays
Weekend = TRUE IF Day > Friday
```

One example of [[User-defined data type]]. 
There could not be a built-in generic definition because the possible values would not be known.
The values can only be known when the programmer has identified them in the type definition.