# Meow
An esotoric programming lanugage written in Rust.

# Features
## Data Types
### Primitives
- [ ] char
- [ ] bool
- [ ] int   (i32)
- [ ] float (f64)
- [ ] null
### Collections
- [ ] list    (variable length, store any data type but only ONE data type)
- [ ] hashmap (key can be string or number (int, float), value can be anything)
- [ ] string  (immutable, technically a colelction of chars)
### Exceptions
- [ ] RuntimeErr ('catch all' for runtime errors)
- [ ] SyntaxErr (Syntax error...)
- [ ] TypeErr (Incompatible operations with a type - only raised during static type checking, e.g. division by a string)
- [ ] NameErr (Name doesnt exist i.e. variable or function wasnt defined yet)

## Expressions
### Logical Operators
- [ ] not 
- [ ] and 
- [ ] or 
### Comparisons
(Expressions with comparisons will evaluate to a bool)
- [ ] X < Y (Less than)
- [ ] X > Y (Greater than)
- [ ] <= (Less than or equal to)
- [ ] >= (Greater than or equal to)
- [ ] == (is equal to)
- [ ] != (is not equal to)
(Comparisons can never be made between different types. User defined types also can only be compared for equality, and only if the user defines the _eq method.)
### Math
- [ ] +  (Addition - can also be used to concatenate str)
- [ ] -  (Subtraction - can also be used to make negative number)
- [ ] /  (Division)
- [ ] // (Int division - truncation)
- [ ] *  (Multiplication)
- [ ] ^  (Raise to the power of)
(Math operations only work on numbers (int, float) with the exception of +)
(Math follows BODMAS and brackets can be used)
## Control Flow
- [ ] if (bool) 
- [ ] for
- [ ] while
- [ ] try (...) catch (opt some RuntimeErr)
- [ ] else 

## Variables
- Declared with the type name
`<type> foo = value`
- Variables have scope to the block / function they are defined in
- Alphanumeric, case-sensitive naming, but cannot start with numbers
- Types have to be declared

## Functions
- Declared with def
- Types of the parameters must be declared, as well as return values
```
def foo(x: <type>, y: <type>, z: <type> = default_value) -> <type> {
  // Stuff here
}
```



