# JavaScript

## VAR

- Globally scoped or (function / local) scoped
- can be re-declared and updated
- initialized as undefined

## Hoisting

- variables and function declarations are moved to the top of their scope before code execution

## LET

- Preferred variable declaration.
- Blocked Scoped
- LET vars are treated as different when in their own scope
- not initialized on read meaning reading data before declaration will read a "reference error"

## CONST

- blocked scoped
- similar to let as they can be accessed only within blocked declared
- can not be updated or redeclared
- const objects key values can be updated

## Key differences

- variables declared with Var are globally scoped or function scoped . Let and const are block scoped at their declaration.

- Variables declared with var can be updated and re-declared within its scope.
- Let variables can be updated but not re-declared
- Const variables can neither be updated nor re-declared.

They are all hoisted to the top of their scope but while varvariables are initialized with undefined, let and const variables are not initialized.

While var and let can be declared without being initialized, const must be initialized during declaration.

Chima, Sarah. Var, Let and Const- What’s the Difference? 8 Jan. 2020, dev.to/sarah_chima/var-let-and-const–whats-the-difference-69e.

## What's a function ?

- sub-task / program designed for a particular task
- Only called when executed
- values can be passed into functions for use
- always return a value so no value will return undefined

## Loops

- can be utilize to look through an array
- using .length property to determine size of an array
- be sure to start a zero when looping through FOR
- also ensure index is less than and not equal too
- use an alias to help clean up naming ex: catArr would create a cat element

- lambda function / anonymous - array functions =>

## Parameter vs Arguments

    - Parameters are used when defining a function values to be supplied ex (param 1, param2 )
    - Their can be up to 255 parameters



    - Arguments are values the functions receives at initialization
