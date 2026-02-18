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

---

## Session 03

#### Introduction to For Loops
 - Running a For loop on a List
 - Understanding For loop components
   - Role of the Alias variable
   - Colon `:` and Indentation structure
 - Running a For loop on `range()` function and `string`
   - Concept of Iterables
 - Running a For loop a certain number of times using `range()` function

#### Basic operations on a List
 - Accessing single items with Indexing operation
 - Comparison operations with `>` and `==` to generate Boolean output 
 - Membership operation with `in` and `not in` operators

 #### Exercises done in session
  - Checking if List items are Even or Odd
  - Checking if List items are +ive (.i.e., > 0)
  - Counting the number of +ive values in a List without using conditional statements
  - Fetching a particular list item with Indexing operation and performing comparison operations on it
  - Does a List have a certain item ?

 ---

 

## Session 04

#### Naming convention for Variables - Dos and Don'ts
 - Can start with lower or UPPER case letters
 - Can start with an underscore `_`
 - Cannot start with numbers or other special characters
 - Variable names that differ only in letter case are treated as different variables, which means Python is case-sensitive
   - e.g., in `year = 2025` and `Year = 2026` , the variables `year` and `Year` are considered two separate variables

#### Role of Indentation in For Loops
* Observed what happens when indentation is present and what changes when it is removed
* Explained that indentation defines the block of code inside the `for` loop, meaning all indented statements are executed as part of the loop

#### Use of `dir()` and `help()` functions on `Lists`
 - `dir(list)` to explore the different methods available for `List` as a data structure
 - `help(list.append)` to check the documentation and usage details for the `append()` method
 - `help(list)` to check the complete documentation available for `List` as a data structure

#### Explored List Methods with examples
 - `append()` --> to add new item to a List at the end
 - `count()`  --> to count the number of occurrences of an item in a List 
 - `clear()`  --> to remove all List items to make it empty
 - `sort()`   --> to sort List items in ascending or descending order

#### Slicing on Lists (brief introduction)
 - Use of Slicing operation to fetch multiple items from a List based on their Index positions
 - Used slicing with various `start`, `stop`, and `step` values to perform meaningful data extraction on a yearly sales example

#### Exercises covered
- Creating a List with 5 random Integers with `random.randint()` function and `append()` method
- Simulating a Coin Toss and storing the outcomes ('Head','Tail') in a list with `random.choice()` function and `append()` method
- Fetching the First 3 items from a List
- Fetching the last 3 items from a List


---

## Session 05

#### Slicing in Detail
- Role of `start`, `end` and `step` components in the way Slicing actually happens
- Effect of `-ive` and `+ive` step value on the direction of Slicing, i.e., `Left to Right` or `Right to Left`
- Covered different variations in slicing for an Yearly Sales example
  - Get Quarter end month sales (.i.e, Mar, Jun, Sep and Dec) 
  - Get Half Year end month sales (.i.e, Jun and Dec)
  - Get sales for Even months (.i.e, Feb, Apr, Jun,..)
  - Get sales for Odd months (.i.e, Jan, Mar, May,..)
  - Get 12 month sales in reverse order (.i.e, Dec, Nov, Oct,....Feb, Jan)
  - Get sales for Odd and Even months but reversed (.i.e, Nov, Sep, Jul, ...) and (.i.e., Dec, Oct, Aug, ...)
  - Creating a Nested List with Quarter sales in inner lists

#### `index()` method in detail
 - Exercises
   - Get position of Student in Top 30
   - Get sales for a month using month name

---


## Session 06

#### Other List Methods covered
 - `remove()` --> to remove a list element based on its value
 - `pop()`    --> to remove a list element based on its index
 - `insert()` --> to add a new item to the List at the desired index position
 - `extend()` --> to extend a list by appending items from another list

#### Conditional Statements (brief introduciton)
 - `if` and `else`
 - Exercise : Identifying Lists values (numeric) as Odd or Even

#### Index based assignment to Lists
 - overwriting the 'NA' value in a List with a value of choice

#### While loops (brief introduction)
 - Explained how a `while` loop differs from a `for` loop (a `for` loop runs over a sequence, while a `while` loop runs based on a condition)
 - Executes repeatedly as long as the given condition remains `True`, and stops when the condition becomes `False`

#### Exercises covered
 - Cleaning a single unwanted value (e.g., `NA`) from a list
 - Cleaning multiple unwanted values (e.g., `NA`) from a list
 - Using the `remove()` method inside a `while` loop to repeatedly eliminate specific values
 - Removing the last item from inner lists within a nested list using the `pop()` method
 - Inserting a new item into inner lists at a specific index position using the `insert()` method
 - Converting a nested list into a single flat list using the `extend()` method

---




## Session 07

#### Other List Methods covered
 - `reverse()` --> to reverse a list
   - or use slicing operation of `[::-1]`
 - `copy()`    --> to create a shallow copy of a list


#### Concept of Shallow and Deep Copy
 - How a simple assignment, i.e. `b = a`, (where `a` is a simple list) does not create a proper list copy, and any changes to `a` will affect `b`
 - How `copy()` method and slicing operation of`[::]` create copies of simple lists which do not get affected when original lists are altered. 
 - That there are limitattions with these methods as they work only for simple lists, but not for Nested Lists
 - For creating independent copies of Nested Lists copies we need something more which is where Deep copies come (to be explored later)


#### Index based assignment to Lists
 - Overwriting/updating list items by using index based assignment operation
   - E.g., `movies[2] = 8.9`
 - **Practical example :** Converting -ive values in a List to positive and overwriting the original list

#### Accessing both Index and Values of List Items
- **Running a for loop on list length** - `for i in range(len(nums)):` to allow fetching both `Index` and `Values` of items
  - To access `Index` use `i`
  - To access `Values` use `nums[i]`

#### Conditional Statements - Use of `if`, `elif`, and `else`
 - E.g., applying conditional statements to assign Grades (A+, A, B...) to Test scores
 - Testing the `if/elif/else` logic on multiple values by using `range()` function - e.g., `for score in range(0,101,10):`
 - Using conditional statement in a single line - examples:
    ```
    'Pass' if score >= 50 else 'Fail'
    ```
    ```
    "Water Vapor" if t >=100 else "Water" if t>0 else "Ice"
    ```

#### Role of `Break` statement in For loops
- Using the `break` statement to stop a `For loop` early when a criteria is met

---
