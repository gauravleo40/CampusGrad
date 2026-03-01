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

## Session 10

#### Limitations of Lists & Tuples → Need of Dictionaries

When we are dealing with real-world data like **product names and their prices**, we want to store information in such a way that both pieces of information stay connected in a meaningful way.

* **Simple List / Tuple (Major limitation)**

  * If we store only prices, we immediately lose the connection between the product and its price
  * E.g.,
    * ```
      prices_list = [25, 60, 45, 120, 15]
      prices_tuple = 25, 60, 45, 120, 15
  * These structures store values only, they do not tell us which price belongs to which product
  * Tuples are even less preferred here because prices tend to change over time, and tuples are immutable

* **Nested List or Nested Tuples (Partial improvement, still indirect)**

  * Using a nested structure, we can now store product name and price together

  * E.g. of a Nested List storing the information
    * ```
      price_nlist = [["Milk", 25], 
                      ["Bread", 60], 
                      ["Eggs", 45], 
                      ["Cooking Oil", 120], 
                      ["Banana", 15]]
    
  * This is definitely better because the association between Product name and Product Price is preserved

  * However, to do something as simple as **Accessing a product’s price** requires a loop

    * ```
      for info in price_nlist:
          if item in info:
              print(info[-1])
      ```

  * Similarly, **Finding the maximum price** also needs a For loop
    * ``` 
      max([info[-1] for info in price_nlist])

  * ❗The overall idea is that while lists and tuples *can* store product–price information using nested structures, accessing specific data or performing operations like finding the maximum price becomes indirect and loop-based

  * **In summary, information retrieval in Lists and Tuples is not direct when association matters and simple tasks require us to iteratively search through the nested structure**


#### Dictionaries as a Data Structure

* Dictionary in Python is another built-in Data Structure, that is ideal for storing information where "association" matters
  * ```
      `prices_dict = {"Milk": 25, 
                      "Bread": 60, 
                      "Eggs": 45, 
                      "Cooking Oil": 120, 
                      "Banana": 15}`

* Here the dictionary has Five items stored as the Five **key : value** pairs
      
  * For each of the Five items (separated by comma), the Product name is stored as the `key` and the Product price is stored at the `value`

* With this structure, accessing a particular product's price becomes a simple Indexing task

  * `prices_dict["Banana"]`
  * This returns 15

* Even aggregate operations become cleaner

  * `max(prices_dict.values())` returns 120
  * `min(prices_dict.values())` returns 15

#### Creating Dictionaries from scratch

- **Storing RGB values for colors** : Information that does not change over time
  ```
  Red   → 255, 0, 0
  Blue  → 0, 0, 255
  Green → 0, 128, 0
  ```

  ```
  {'Red': (255,0,0), 
  'Blue': (0,0,255), 
  'Green': (0,128,0)}
  ```
- **Storing Movie information** : Information can change since ratings can upgrade or downgrade
  ```
  'The Dark Knight', 2008, 9, 1791916, 'Christopher Nolan'
  'Inception', 2010, 8.8, 1583625, 'Christopher Nolan',
  'Dangal', 2016, 8.8, 48969, 'Nitesh Tiwari',
  'Interstellar', 2014, 8.6, 1047747, 'Christopher Nolan'
  ```

  ```
  {'The Dark Knight': [2008, 9, 1791916, 'Christopher Nolan'],
         'Inception': [2010, 8.8, 1583625, 'Christopher Nolan'],
            'Dangal': [2016, 8.8, 48969, 'Nitesh Tiwari'],
      'Interstellar': [2014, 8.6, 1047747, 'Christopher Nolan']}
  ```

#### Key based indexing in Dictionaries

* **Dictionaries do not have integer-based indexing like Lists or Tuples**
  - In lists we access elements using positions such as `prices_list[0]`, but Integer Indexes do not apply for dictionaries (its items are not ordered)
  - Dictionaries are organized by association. Therefore, something like `prices_dict[0]` does not work unless `0` itself is a key in the dictionary.

* **Dictionaries still support indexing, but it is key-based indexing**
  - When we write `prices_dict["Milk"]`, Python returns the value associated with the key `"Milk"`. 
  - In other words, key-based indexing in Dictionaries retrieves the mapped value corresponding to a specific key.

* **Key-based indexing to add new items to a dictionary**
  - `prices_dict["Apple"] = 250` will add a new item to the dictionary
  - Here the key "Apple" does not already exist in dictionary, thus assignment creates a new key–value pair
  - So in dictionaries, indexing combined with assignment becomes a way of expanding the data structure.

* **Key-based indexing to update exisitng items in a dictionary**
  - `prices_dict["Apple"] = 300` will update the price for Apples in Dictionary
  - If the key "Apple" already exists in Dictionary, then assigning a new value will update it
  - The key remains the same, only the associated value changes.

#### Keys in Dictionaries are unique

* **Dictionaries do not allow multiple keys with the same name because a key is like a unique label for a value**. Think of the key as a student’s roll number : two students cannot share the same roll number because then we would not know which student we are referring to.

* For example, if we try to create a dictionary like:
  `{"Apple": 250, "Apple": 300}`
  Python will not store two separate entries. It will simply keep the latest value, resulting in:
  `{"Apple": 300}`

* This happens because in a dictionary, each key can point to only one value at a time. When we write `prices_dict["Apple"]`, Python must return exactly one value. **If duplicate keys were allowed, Python would not know which one to return**

* So the rule is simple: **One key → One value.** That is why dictionary keys must always be unique.

---

## Session 11

#### Dictionary creation
- Creating an empty dictionary
  - `scores = {}`
- Iteratively adding items to the dictionary
    ```
    names = ['Ken','Roger','Joan','Stan']
    marks = [87, 73, 91, 80]
    for idx,name in enumerate(names):
        scores[name] = marks[idx]
    ```
- Using `zip()` and `dict()` functions to create a Dictionary
    ```
    #-----Example 01 : Single attribute (marks)--------
    names = ['Ken','Roger','Joan','Stan']
    marks = [87, 73, 91, 80]
    scores = dict(zip(names,marks))
    ```

    ```
    #-----Example 02 : Multiple attributes (age and marks)--------
    names = ['Ken','Roger','Joan','Stan']
    marks = [82, 49, 88, 85]
    age = 34,23,26,17
    scores = dict(zip(names,zip(age,marks)))
    print(scores)

    #---output----
    {'Ken': (34, 82), 'Roger': (23, 49), 'Joan': (26, 88), 'Stan': (17, 85)}
    ```

#### Operations on a Dictionary

```
d = {'The Dark Knight': [2008,9,1791916,'Christopher Nolan',533.32],
                'Inception': [2010,8.8,1583625,'Christopher Nolan',292.57],
                'Dangal': [2016,8.8,48969,'Nitesh Tiwari',11.15],
                'Interstellar': [2014,8.6,1047747,'Christopher Nolan',187.99]}
```


- Adding a new item with key based **Indexing + Assignment**
  - `d["The Departed"] = [2006, 8.5, 937414, 'Martin Scorsese', 132.37]`
- Deleting an existing item with `pop()` method
  - `d.pop('Interstellar')`
- Adding items in dictionary `d` from another dictionary `more_movies`
  - `d.update(more_movies)`
- Checking if an item exists in a dictionary - **Membership operation on a Dictionary**
  - `kantara in d` returns a `False`
  - `Dangal in d` returns a `True`


#### Running For loop on a Dictionary - to access its different components
- Accessing `keys` of a Dictionary
  - `for i in d :`
  - `for i in d.keys() :`
- Accessing `values` of a Dictionary
  - `for i in d.values() :`
- Accessing `items` of a Dictionary
  - `for i in d.items() :`

---
