# Learning Rust

Programs based on the official Rust Book 2.0

## Summary

1. [hello_world](./hello_world/main.rs)
    * Use `println!` macro
2. [hello_cargo](./hello_cargo/src/main.rs)
    * Use cargo package manager
3. [guessing_game](./guessing_game/src/main.rs)
    * Use external crate(`rand`)
    * Defining a *trait*
    * Creating new variables with `let`
    * Creating new mutable variables with `mut`
    * Using __associate__(static) methods with `::`
    * Type annotations
    * Variable shadowing
    * Handling results
    * Using `loop`s
    * Using `break`
    * Using `match`
    * Using `cmp`
    * Using `rand`...
4. [variables](./variables/src/main.rs)
    * Declaring immutable variables with `let`
    * Declaring mutable variables with `mut`
    * Declaring constants with `const`
    * Value and type shadowing
    * Differnce between the three types
5. [data_types](./data_types/src/main.rs)
    * Declaring scalar and compound data-types(tuple and arrays)
    * Declaring variables with types (& sometimes size)
    * Creating fixed length arrays
    * Accessing elements of compound data-types
6. [functions](./functions/src/main.rs)
    * Creating functions using `fn`
        * with parameters and return types(appended after `->`)
        * with explicit returns
        * with implicit returns
7. [control_flow](./control_flow/src/main.rs)
    * Using `if`/`else`/`else if`
    * Using conditional as expressions
    * Creating and `break`ing `loop`s
    * That `break` return the value of the following expression
    * Using `while`
    * Using `for`
    * Using `..` to generate range
    * Using `iter()` method to iterate through an array
    * Using `rev()` method to reverse a range
8. [f2c](./f2c/src/main.rs)
    * Using function on strings
    * Dabble into iterators
    * Using `if` conditional
    * Creating functions with `fn`
9. [fibonacci](./fibonacci/src/main.rs)
    * Used recursive function
    * Alternative using iteration
    * Learned that Rust still doesn't support destructuring assignment
    * And also no sane way to use yield
    * The iterative alt. function has a bug!
10. [christmas_song](./christmas_song/src/main.rs)
    * More conditionals
    * Using `..` operator for iteration
    * That `{:?}` is for debug purposes
