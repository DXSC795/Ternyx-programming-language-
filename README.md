

Guawa Language Specification

*Syntax and Semantics*

- Consistent naming conventions: camelCase
- Simplified comments: `//` (single-line), `/* */` (multi-line) replaced with `//` (single-line), `///` (multi-line)
- Clarified code block syntax: indentation-based, with clear rules for scope

*Data Types*

- Added date and time types: `date`, `time`, `datetime`
- Introduced nullable types: `?type` (e.g., `?kal`, `?nexa`)
- Enhanced numeric types: unsigned integer types (`uint`), arbitrary-precision numeric type (`arb`)

*Control Flow*

- Added switch statement: `switch (expression) « ... »`
- Enhanced loop constructs: foreach loop (`foreach (item in collection) « ... »`)

*Functions*

- Function overloading: allowed
- Type inference: improved for function parameters and return types
- Lambda expression syntax: simplified (`(params) => expression`)

*Error Handling*

- Enhanced error types: specific error types (e.g., `TypeError`, `ValueError`)
- Improved try-catch syntax: simplified (`try « ... » catch (error) « ... »`)

*Operators*

- Added bitwise operators: `&`, `|`, `^`, `~`
- Considered operator overloading: allowed for user-defined types

*Miscellaneous*

- Module system: introduced (`module`, `into`, `exto`)
- Macros or meta-programming: introduced (`macro`, `meta`)
- Concurrency support: introduced (`async`, `await`)

*Keywords*

- `omit` -> `if`
- `swot` -> `else`
- `surge` -> `while`
- `torvik` -> `for`
- `dox` -> `def`
- `vokar` -> `print`
- `kalt` -> `input`
- `fib` -> `return`
- `threx` -> `and`
- `flux` -> `or`
- `sygma` -> `not`

*Operators*

- `+` (addition)
- `-` (subtraction)
- `*` (multiplication)
- `/` (division)
- `==` (equality)
- `!=` (inequality)
- `<` (less than)
- `>` (greater than)
- `<=` (less than or equal)
- `>=` (greater than or equal)
- `&&` (Logical AND)
- `||` (Logical OR)
- `!` (Logical NOT)
- `&` (bitwise AND)
- `|` (bitwise OR)
- `^` (bitwise XOR)
- `~` (bitwise NOT)

*Data Types*

- `kal` (Integer)
- `nexa` (Float)
- `date` (Date)
- `time` (Time)
- `datetime` (DateTime)
- `?type` (Nullable type)
- `uint` (Unsigned Integer)
- `arb` (Arbitrary-precision numeric)
- `vix` (String)
- `dual` (Boolean)
- `sek` (List)
- `kor` (Tuple)
- `mapa` (Dictionary)
- `void` (Null)
- `unin` (Undefined)

*Function Declaration*

`def function_name(parameters) « code »`

*Example Code*

```
Guawa
// Into module
into math

// Define function
def greet(name: vix) «
  print"Hello, " + name + "!")
»

// Call function
greet('Ternyx")

// Use macro
macro double(x) «
  x * 2
»

// Use concurrency
async function asyncExample() «
  await print(‹Async example›)
»