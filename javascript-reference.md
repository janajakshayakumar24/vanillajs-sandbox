# Javascript Reference

## Table of Contents
- [Introduction](#introduction)
- [Values](#values)
    - [Literals](#1-literals-fixed-values)
    - [Variables](#2-variables-variable-values)
- [Datatypes](#datatypes)
- [Operators](#operators)
- [Conditional Statements](#conditional-statements)
- [Loops](#loops)

## Introduction
Javascript is a lightweight, interpreted (or just-in-time compiled), single-threaded, object-oriented programming language with first-class functions.

- High-level and interpreted (JIT):
    - JS abstracts low-level memory management (automatic garbage collection).
    - Interpreted language (Just-In-Time Compilation): Code is compiled into machine code at runtime - makes it fast.

- Single-threaded and Asynchronous:
    - JS runs on a single main thread: executes one command at a time.
    - Handles complex, non-blocking asynchronous operations (like API fetching or timers) using Event Loop, Callbacks, Promises, and Async/Await.

- First-class functions:
    - Functions are treated like variables: They can be stored in variables, passed as arguments to other functions, and returned from functions.

- Prototype-based object-orientation:
    - JS used prototypal inheritance: Objects inherit properties and methods directly from other objects via a prototype chain.

- JS spans entire development stack:
    1. Client-side (the browser):
        - JS controls the behavior of the webpage (logic).
        - It manipulates DOM, handles user events, and powers frameworks like React, Vue, and Angular.
    2.  Server-side (the backend):
        - JS can be run directly on a machine or server, handling file systems, databases, and APIs using Node.js.

## Values

### 1. Literals (Fixed values)  
```js
    1234
    "hello"
```

### 2. Variables (Variable values)
- containers for storing values
- must be identified with unique names (identifier: name given to a variable)
- rules for identifiers:
    - must start with letter, _, or $
    - can contain digits after first character
    - no reserved keywords
    - case sensitive
```js
    var
    let
    const
```

## Datatypes
> 1. number
> 2. string
> 3. boolean
> 4. undefined
> 5. null
> 6. object
> 7. bigint
> 8. symbol

## Operators
- for mathematical and logical computations.

1. Arithmetic
```js
    +
    -
    *
    /
    ++
    --
    **
    %
```  

2. Assignment
```js
    =  
    +=  
    -=  
    *=  
    /=  
    **=
    %=
```

3. Comparison
```js
    ==  
    ===
    !=  
    !==  
    >
    <
    >=
    <=
```

4. Logical
```js
    &&
    ||
    !
```

## Conditional Statements
```js
    if () {
        // code block
    }
```

```js
    if () {
        // code block
    }
    else {
        // code block
    }
```

```js
    if () {
        // code block
    }
    else if () {
        // code block
    }
    else {
        // code block
    }
```

```js
    switch () {
        case 'x':
            // code block
            break;
        case 'y':
            // code block
            break;
        default:
            // code block
    }
```

```js
    () ? () : () // ?: ternary operator
```

## Loops
```js
    for (let i = 0; i < 10; i++) {
        // code block
        // break;
    }
```

```js
    for (variable in object) {
        // code block
        // break;
    }
```

```js
    for (variable of iterable) {
        // code block
        // break;
    }
```

```js
    while (i < 10) {
        // code block
        // break;
    }
```

```js
    do {
        // code block
        // break;
    }
    while (i < 10)
```