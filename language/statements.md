---
title: Statements
layout: default
parent: Documentation
nav_order: 3
---

# Statements

## If/Else

Use the following syntax:

```ruby
@intVar = 5
if intVar > 6 {
    
} else {
    
}
```

If statements are not required to contain the else statement, but do require the ending curly brace as in other
languages.

The first operand of the if statement must be a variable. The second can optionally be a variable.

### Conditional Operators

- `==` Is
- `!=` Is Not
- `contains` Contains
- `!contains` Does Not Contain
- `beginsWith` Begins With
- `endsWith` Ends With
- `>` Greater Than
- `>=` Greater or Equal
- `<` Less Than
- `<=` Less or Equal

### Has Value/Does Not

```go
// Has Any Value
if intVar {
    
}
// Does not have any value
if !intVar {
    
}
```

### Between

This checks if `intVar` is between `5` and `7`.

```go
if intVar <> 5 7 {
    // ...
}
```

## Loops

### Repeat

Use the following syntax:

```ruby
@items
repeat 6 {
    @items += "Item {RepeatIndex}"
}
```

The number after repeat could also be a variable as long as it evaluates to a number value.

### Repeat With Each

Use the following syntax:

```ruby
@items = list("item 1","item 2","item 3")
for list {
    alert(RepeatIndex,RepeatItem)
}
```

`list` must be an iterable variable.

### Repeat Globals

In `repeat`, the `RepeatIndex` is accessible.

In `foreach` (repeat with each), `RepeatIndex` and `RepeatItem` are available.

## Nesting

`if/else`, `repeat`, `foreach`, and `menu` can all be nested inside each other and vice versa.
