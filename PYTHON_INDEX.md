## `pmz.py`

**Functionality:** This script is a web crawler designed to download images from the website `www.dbmeinv.com`. It navigates through different pages of the site and saves the images it finds.

**Python Concepts Demonstrated:**
- Modules and Libraries: `urllib.request` for fetching URLs, `bs4` (BeautifulSoup) for parsing HTML.
- Functions: Defines and uses a custom function `crawl()` to encapsulate the scraping logic for a single page.
- Loops: Uses a `for` loop to iterate over a range of pages and another `for` loop to iterate over found image elements.
- File I/O: Opens and writes image data to local files in binary mode (`'wb'`).
- String Manipulation: Uses string slicing to construct filenames.
- HTTP Requests: Makes HTTP GET requests to web pages and image URLs.

[Link to script](./pmz.py)
---
## `python_base.py`

**Functionality:** This file is a comprehensive Python cheat sheet or reference guide. It does not perform a specific task as a program but rather serves as a knowledge base, containing extensive notes, comments, and example code snippets that explain a wide array of Python's syntax, features, and programming concepts.

**Python Concepts Demonstrated:**
This file itself is a demonstration of how to document and explain Python. It covers, through comments and examples, nearly the entire spectrum of Python, including (but not limited to):
- Basic data types (integers, floats, strings, booleans)
- Data structures (lists, tuples, dictionaries, sets)
- Operators (arithmetic, comparison, logical, bitwise)
- Control flow (if/else, for/while loops)
- Functions (definition, arguments, scope, lambda functions, generators)
- Object-Oriented Programming (classes, inheritance, methods, properties, decorators)
- Modules and Packages (importing, structure, `__init__.py`)
- Error Handling (try/except/else/finally, custom exceptions)
- File I/O
- String manipulation and formatting
- Unicode and byte strings
- Built-in functions and standard library examples.

Due to its nature as a reference file, it touches upon how these concepts are written and used in Python.

[Link to script](./python_base.py)
---
## `例子-0829-01.py`

**Functionality:** This script demonstrates basic user input using the `input()` function and output using the `print()` function. It also illustrates how to write single-line and multi-line comments in Python. It makes a note about `raw_input()` from Python 2.

**Python Concepts Demonstrated:**
- User Input: `input()`
- Output: `print()`
- Variables: Assigning input to a variable.
- Comments: Single-line (`#`) and multi-line (`'''...'''`).
- Strings: Basic handling of string data.

[Link to script](./例子-0829-01.py)
---

## `例子-0829-02.py`

**Functionality:** This script showcases various ways to use the `print()` function, including printing literal strings, variables, results of expressions, and using older style string formatting with `%s` (for strings) and `%d` (for integers). It also demonstrates type conversion using `int()`.

**Python Concepts Demonstrated:**
- Output: `print()`
- Variables: Storing and printing variable values.
- String Operations: Concatenation.
- Arithmetic Operations: Basic addition.
- Built-in Functions: `abs()` for absolute value.
- String Formatting: Using the `%` operator for basic string formatting.
- Type Conversion: `int()` to convert a string to an integer.
- User Input: `input()`.

[Link to script](./例子-0829-02.py)
---

## `例子-0829-03.py`

**Functionality:** This script provides examples of Python's basic arithmetic operators.

**Python Concepts Demonstrated:**
- Arithmetic Operators: `+` (addition), `-` (subtraction), `*` (multiplication), `/` (true division), `%` (modulo), `**` (exponentiation), `//` (floor division).

[Link to script](./例子-0829-03.py)
---

## `例子-0829-04.py`

**Functionality:** This script demonstrates the use of logical operators in Python.

**Python Concepts Demonstrated:**
- Logical Operators: `and`, `or`, `not`.
- Boolean Expressions: Combining comparison results.

[Link to script](./例子-0829-04.py)
---

## `例子-0829-05.py`

**Functionality:** This script illustrates comparison operators with numbers and strings. It highlights that string comparison is based on character codes (lexicographical comparison).

**Python Concepts Demonstrated:**
- Comparison Operators: `==` (equal to), `>=` (greater than or equal to), `>` (greater than).
- Boolean Expressions.
- String Comparison: Lexicographical comparison of characters.

[Link to script](./例子-0829-05.py)
---

## `例子-0829-06.py`

**Functionality:** This script demonstrates `for` loops iterating over different sequence types (string, list, tuple) and the `in` operator for checking membership within a string.

**Python Concepts Demonstrated:**
- Loops: `for` loop.
- Iteration: Iterating through characters in a string, items in a list, and items in a tuple.
- Data Structures: Strings, Lists, Tuples.
- Membership Testing: `in` operator.

[Link to script](./例子-0829-06.py)
---

## `例子-0829-07.py`

**Functionality:** This script shows a simple conditional statement using `if` to check user input against a specific string value.

**Python Concepts Demonstrated:**
- Conditional Statements: `if`.
- User Input: `input()`.
- String Comparison.
- Conditional Execution.

[Link to script](./例子-0829-07.py)
---

## `例子-0829-08.py`

**Functionality:** This script demonstrates an `if-else` conditional structure. It takes an integer input (age) and makes a decision based on whether the age falls within a certain range using a compound condition with `and`.

**Python Concepts Demonstrated:**
- Conditional Statements: `if-else`.
- User Input: `input()`.
- Type Conversion: `int()`.
- Comparison Operators: `>`, `<`.
- Logical Operators: `and`.
- Conditional Execution.

[Link to script](./例子-0829-08.py)
---

## `例子-0829-09.py`

**Functionality:** This script demonstrates a multi-way conditional structure using `if-elif-else` to check user input against several different string values.

**Python Concepts Demonstrated:**
- Conditional Statements: `if-elif-else`.
- User Input: `input()`.
- String Comparison.
- Multi-way Conditional Execution.

[Link to script](./例子-0829-09.py)
---
## `例子-0830-01.py`

**Functionality:** This script demonstrates `for` loops iterating over different types of sequences: a string, a tuple, and numerical ranges generated by the `range()` function (with one and two arguments).

**Python Concepts Demonstrated:**
- Loops: `for` loop.
- Iteration: Over strings, tuples.
- `range()` function: Generating sequences of numbers.
- Data Structures: Strings, Tuples.

[Link to script](./例子-0830-01.py)
---
## `例子-0830-02.py`

**Functionality:** This script illustrates a `while` loop that continues as long as a condition (`a<10`) is true. Inside the loop, a variable `a` is incremented, and an `if` condition checks its value. It also includes comments about creating infinite loops.

**Python Concepts Demonstrated:**
- Loops: `while` loop.
- Conditional Statements: `if`.
- Variables: Incrementing (`+=`).
- Loop Control: Basic condition-based looping.
- Infinite Loops: Conceptual note.

[Link to script](./例子-0830-02.py)
---
## `例子-0830-03.py`

**Functionality:** This script shows the use of the `continue` statement within a `while` loop to skip the rest of the current iteration and proceed to the next. A `break` statement is present but commented out.

**Python Concepts Demonstrated:**
- Loops: `while` loop.
- Conditional Statements: `if`.
- Loop Control Statements: `continue` (active), `break` (commented out).

[Link to script](./例子-0830-03.py)
---
