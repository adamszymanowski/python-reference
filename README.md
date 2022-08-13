# Python Reference
This is my own guide to Python, that I will use as my own reference. It's mostly based on [Python Standard Library official documentation](https://docs.python.org/3/library/), and in some cases I will quote this documentation directly.

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

Whether exception occurs or not do this no matter what

`for`

Iterate over items of sequence (or iterable)

`from`

Import specific part of a module

`global`

Inside a code block declare a variable as `global` so it can be modified from the inside 

`if`

Condition check.

`import`

Import a module.

`in`
1. Check whether a sequence contains an element
2. Part of `for` loop

`is`

Check object identity (whether it's the same object).



`lambda`


`nonlocal`


`not`
Boolean not.

`or`
Boolean or. This is a short-circuit operator, so it only evaluates the second argument if the first one is false

`pass`


`raise`


`return`


`try`


`while`


`with`


`yield`


`True`

The true value of the bool type.

`False`

The false value of the bool type

`None`

An object frequently used to represent the absence of a value, as when default arguments are not passed to a function.



**References**
[keyword list](https://www.programiz.com/python-programming/keyword-list)
- [import, as](https://docs.python.org/3/reference/simple_stmts.html#import)
- [boolean operations](https://docs.python.org/3/library/stdtypes.html#boolean-operations-and-or-not)
- [assert](https://docs.python.org/3/reference/simple_stmts.html?highlight=assert#the-assert-statement)
- [assert keyword](https://www.geeksforgeeks.org/python-assert-keyword/)
- [await](https://docs.python.org/3/reference/expressions.html#await)
- [control flow, break, continue](https://docs.python.org/3/tutorial/controlflow.html)
- [define class](https://docs.python.org/3/tutorial/classes.html?highlight=class#class-definition-syntax)
- [defining functions](https://docs.python.org/3/tutorial/controlflow.html#defining-functions)
- [del](https://www.programiz.com/python-programming/del)
- [handling exeptions](https://docs.python.org/3/tutorial/errors.html#handling-exceptions)
  * [exception handling](https://www.programiz.com/python-programming/exception-handling)
- [for](https://docs.python.org/3/tutorial/controlflow.html#for-statements)
  * [for loop](https://www.programiz.com/python-programming/for-loop)
- [global](https://docs.python.org/3/reference/simple_stmts.html?highlight=global#the-global-statement)
  * [global keyword](https://www.programiz.com/python-programming/global-keyword)

- [True, False, None](https://docs.python.org/3/library/constants.html?highlight=false#False)



## Built-in functions
[built-in functions documentation](https://docs.python.org/3/library/functions.html)