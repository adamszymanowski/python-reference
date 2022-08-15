# Python
Reference for python (without built-in modules, this in a separate file). This means keywords, built-int functions, types, etc.

## Keywords
[keywords documentation](https://docs.python.org/pl/3/reference/lexical_analysis.html#keywords)

`and`

Boolean and. This is a short-circuit operator, so it only evaluates the second argument if the first one is true

`as`
1. part of `with` statement
2. `import` module_name `as` alias (rename)

`assert`

Check condition, on `False` raise `AssertionError` with optional message

`await`

Suspend the execution of coroutine on an awaitable object. Can only be used inside a coroutine function.

`break`

Breaks out of the innermost enclosing `for` or `while` loop.

`class`

Define a class.

`continue`

Continues with the next iteration of the loop.

`def`

Define a function.

`del`

Delete user defined class, variable, list slice or dict key:value

`elif`

optional condition check branch after `if` is false, there can be many `elif` branches

`else`

optional branch after either `if` or final `elif` is false

`except`

When exception occurs then do this

`finnaly`

Whether exception happens or not do this no matter what

`for`

Iterate over items of sequence (or iterable)

`from`

Import specific parts of a module

`global`

Inside a function declare a variable as `global` so it can be modified from the inside

`if`

Condition check

`import`

Import a module

`in`
1. Check whether a sequence contains an element
2. Part of `for` loop

`is`

Check object identity (whether it's the same object)

`lambda`

Create short anonymous function

`nonlocal`

Inside a nested function declare a variable as `nonlocal` so it can be modified (it must refer to variable in first outer function)

`not`

Boolean not

`or`

Boolean or. This is a short-circuit operator, so it only evaluates the second argument if the first one is false

`pass`

This code block does nothing.

`raise`

Raise an exception or re-raise current active exception

`return`

Exit a function and return a value

`try`

Try this, but when exception occurs, go to `except` block

`while`

While loop

`with`

With an expression as a variable do this (context manager)


`yield`

Pause here and return (a generator) to caller

`True`

The true value of the bool type.

`False`

The false value of the bool type

`None`

Represents "no value"



## Built-in functions
[built-in functions documentation](https://docs.python.org/3/library/functions.html)

`abs()`

Return the absolute value of a number

`aiter()`

Return an asynchronous iterator or asynchronous iterable

`all()`

Return `True` if all elements in iterable are true or if iterable is empty

`anext()`

When awaited, return the next item from asynchronous iterable

`any()`

Return `True` if any element of iterable is true. 
If the iterable is empty, return `False`


`ascii()`

As `repr()`, return a string containing a printable representation of an object, but escape the non-ASCII characters in the string returned by `repr()` using `\x`, `\u`, or `\U` escapes

`bin()`

Convert an integer number to a binary string prefixed with `0b`

`bool(x)`

Return a Boolean value, either `True` or `False`. `x` is converted using the standard truth testing procedure. 

`breakpoint()`

This function drops you into the debugger at the call site.

`bytearray()`

Return a new array of bytes