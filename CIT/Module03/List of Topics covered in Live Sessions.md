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

## Session 08

#### Additional controls in For Loops
 - `break` statement
 - `continue` statement



#### Nested For loops
 - Running a `For loop` inside another `For loop`
 - *observe the below program in* [Python Tutor](https://pythontutor.com/visualize.html#mode=edit$0)
    ```
    for i in [100,200]:
        for j in [10,20]:
            print(i+j)     
    ```  
    Output  
    ```
    110
    120
    210
    220
    ```

#### Running a For loop with multiple variables
 - Uptill now, For loop used as `for i range(10):`
 - How to run the for loop on multiple variables - lets' say on both `i` and `j` ?
   - `for i,j in <COLLECTION>:`
   - This `<COLLECTION>` will be different from a normal `List` or `range()`
   - Example of such a `<COLLECTION>`: `[[1,2],[3,4],[5,6]]` or `[(0,100),(1,200),(2,300)]`
   - This kind of structures comes under the `enumerate()` function


#### `enumerate()` function
 - Use : To access both `index` and `value` components of items in a List (or other iterables)
 - Observed the structure of `enumerate()` function output by using `list(enumerate(nums))` where `nums` is a simple list
 - Example : *observe the below program in* [Python Tutor](https://pythontutor.com/visualize.html#mode=edit$0)
    ```
    nums = ['A','B','C']
    
    print(list(enumerate(nums)))

    for i,j in enumerate(nums):
        print(i,j)
    ```
    Output

    ```
    [(0, 'A'), (1, 'B'), (2, 'C')]
    0 A
    1 B
    2 C
    ```
  - The following assignment happens under each iteration:
    ```
    i,j = (0,'A')    #---Iteration 01
    i,j = (1,'B')    #---Iteration 02
    i,j = (2,'C')    #---Iteration 03
    ```
 - **This is the Tuple unpacking** in action to assign values to multiple variables in a single line

#### Tuples as a Data Structure

- **Tuples overview**
  - Understanding how Tuples are different from Lists
  - Exploring methods under Tuples - count() and index()
  - Declaring Tuples with and without round brackets - `()`
  - Declaring Tuples with a single item - `t = (100,)` or `t = 100,`

- **Tuples as an immutable Data Structure**
  - Operations **NOT** possible with Tuples
    - Adding new items
    - Removing existing items
    - Updating/ overwriting existing items with Index based assignment operation - i.e., `t[0] = 1`
  - Declaring multiple variables using **Tuple unpacking**
    - E.g, `P,I,T = 10000,0.075,5`
    
  ---

## Session 09

#### List Comprehension
 - A more Pythonic and concise way to generate lists using For loops
   - E.g., `[i**2 for i in range(1,6)]` returns a list `[1,4,9,16,25]`
 - **Structure of a simple List Comprehension**
   - `[<expression> <for loop on an iterable>]` 
 - **Structure of List Comprehension with Conditional Statement**
   - `[<expression> <for loop on an iterable> <Conditional Statement>]`
   - E.g.,  `[i**2 for i in range(1,11) if i%2==0]` returns a list `[4,16,36,64,100]`
 - **Another variation : Note this does not apply any filter on the original list**
   - `[<Conditional Statement> <for loop on an iterable>]`
   - E.g., `["Even" if i % 2 == 0 else "Odd" for i in range(1, 6)]` returns a list `['Odd', 'Even', 'Odd', 'Even', 'Odd']`

#### While Loops
 - Used when the number of loop iterations are not known in advance
 - A `while` loop requires a condition to run. It runs as long as this condition is `True` 
    ```
    while <condition> :
        ---do this---
    ```
 - **Example : Adding numbers entered by a user until they choose to stop**
   - The loop keeps adding numbers entered by a user until they type "stop", so the number of iterations is unknown beforehand.
    ```
    total = 0

    num = input("Enter a number (type 'stop' to finish): ")

    while num != "stop":
        total += int(num)
        num = input("Enter a number (type 'stop' to finish): ")

    print("Total =", total)
    ```
 - **Other examples :**
   - A loop keeps rolling a dice (simulation) until a 6 appears
   - A loop keeps retrying an OTP verification process until the correct OTP is entered or attempts run out.
 - **Important components of a `while` loop**
   - **Initialization :** A variable is usually initialized before the loop starts
   - **A Criteria or a Condition :** that allows the program to enter into the `while` loop and allows it to run untill the condition remains `True`
   - **Update mechanism :** Inside the loop, something must change so that eventually the condition becomes False. Otherwise, the loop becomes an infinite loop

---
