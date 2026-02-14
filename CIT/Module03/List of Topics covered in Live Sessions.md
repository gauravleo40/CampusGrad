# List of topics covered in Live Sessions

## Session 01

#### Introduction to Google Colab 
  - Interface, Navigation and Shortcuts
  - Code execution, markdown, etc.
#### Arithmetic operators
  - `+`, `-`, `*` and `/` for addition, subtraction, multiplication and division respectively
  - `/` division operation always return a Float type
#### Assignment Operators 
  - assignment with = sign
#### Comparison Operators
  - `>`, `<`, `>=`, `<=`
  - `==` to check if LHS is equal to RHS
  - `!=` to check if LHS is NOT equal to RHS
#### Data Types in Python
  - `Integer`, `Float`, `String`, `Boolean`
  - Declaring `Strings` using single, double and triple quotes
#### Python Functions to start with 
  - Concept of functions
  - `type()` function to check the data type of :
    - values : `integer`, `float`, `string`, `boolean`
    - data structures : `list`, `tuple`, `dictionary`, `set`, etc.
  - `print()` function to print output of an expression or a string
#### Concept of Variables and their need
  - Explained the concept and relevance of variables
    - To store data (numbers, text, lists, etc.) by giving meaningful names
    - To reuse values later in the program
    - To avoid repeating hard-coded values
    - To make programs dynamic (values can change)
  - Defining simple variables using the assignment operator `=`
  - Explaining how assignment works in a complication operation, e.g., `final_value = 45 * 3 - 90 / 34 >= 100`
  - Explained how variable values get overwritten by using the same variable names
  - Explained the limitations of variables
#### Other Assignment Operators
  - `+=`, `-=`, `*=`, `/=`  
#### Introduction to Lists as Data Structures
  - Explaining the need and advantages of having data structures:
    - Storage of multiple values without using multiple variable names
    - Ease of performing operations by applying built-in functions
  - Defining a simple list of movie information
  - Defining a simple list of numbers
    - Applying functions `sum()`, `len()`, `max()` and `min()` on list with numeric values

---

## Session 02

#### `print()` function in more detail
- Using multiple commas in a single `print()` function to display text, values, or both together
- Using `f-string` in `print()` to easily include variables inside a sentence for clearer and cleaner output
- Generating decorated output using `print()` with variables
  - example : table of numbers
  - example : displaying movie informaton as a paragrpah

#### `help()` function to look for documentation on a python topic
- e.g., `help(print)`

#### `range()` function to create a sequence of integers
- Explained all three arguments : start, end, step (+ive and -ive)
- Explained how the `range()` function behaves when one, two or all three inputs are passed in it
  - `range(10)`
  - `range(3,10)`
  - `range(5,51,5)`

#### `list()` function to convert a range of numbers in a list
- e.g., `list(range(10))` --> `[0,1,2,3,4,5,6,7,8,9]`
- Explained multiple practical examples to apply `list(range(...))`
  - get year values, `[2026,2025,2024,....,2020]`
  - get table of numbers `[5,10,15,....,45,50]`


#### `random` module to generate information for practice
- `random.choice(range(1,100))` --> to select a single value randomly from `range(1,100)`
- `random.sample(range(1,100),5)` --> to create a sample of size 5 from `range(1,100)`

