# 🟢 Getting Started

Before diving into Python programming, it's helpful to learn a few basic rules. These ideas will make your code easier to read, understand, and troubleshoot. Let’s walk through some simple but important concepts to get started the right way.


## ✅ Case Sensitivity

Python is **case-sensitive**. This means `Name`, `name`, and `NAME` are all considered different. Always pay attention to your spelling and letter case when writing code.

```python
name = "Alex"
Name = "Jordan"
print(name)  # Will print: Alex
print(Name)  # Will print: Jordan
```


## 🧾 Naming Convention

There are some common rules for naming variables in Python:

#### ✅ Valid
* A variable name must start with a letter or the underscore character
  Example: `firstname`, `first_name`, `age`, `_if` # reserved word as a variable
* Use **lowercase letters** and words separated by underscores (snake_case)
  Example: `user_name`, `total_amount`
* A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )

#### ⛔ Invalid
* Names **cannot start with a number**
  `2name` → Invalid
* Avoid using spaces or special symbols in variable names
  `total_amount$`, `user-name`, `first@name`, `variable-1`
* Do not use Python keywords like `class`, `print`, or `for` as variable names

Choose meaningful names that explain what the variable holds.


## 📦 Variables

Variables store values in computer memory. In Python, you do not need to declare the type of a variable before using it. You just give it a name and assign a value using the `=` symbol.

#### 🔹 Declaring a Variable

```python
name = "Akhil"
age = 15
is_student = True
```

In the example above:

* `name` holds a string value
* `age` holds an integer
* `is_student` holds a boolean (True or False)

Python figures out the type based on the value you assign.

#### 🔄 Changing a Variable’s Value

You can assign a new value to the same variable at any time.

```python
name = "Akhil"
name = "AbhiRaam"  # Now name refers to "AbhiRaam"
```

The most recent assignment is what the variable holds.

#### 📌 Multiple Variables in One Line

Python lets you assign values to multiple variables at once. This can help you write cleaner code when needed.

`Example 1: Assigning Different Values`

```python
x, y, z = 1, 2, 3
print(x)  # Output: 1
print(y)  # Output: 2
print(z)  # Output: 3
```

Make sure the number of variables and values match.

`Example 2: Assigning Same Value to Multiple Variables`

```python
a = b = c = 10
print(a)  # Output: 10
print(b)  # Output: 10
print(c)  # Output: 10
```

This is useful when you want to initialize several variables with the same starting value.


## 📏 Indentation in Python

In Python, **indentation is not optional - it is required**. It tells Python which lines of code belong together. If the indentation is incorrect, your code will not run. Indentation means leaving spaces at the beginning of a line to show that it is inside a block, like a loop or a function. In most cases, you press the **Tab** key or type **4 spaces**.

#### ✅ Best Practices to Follow

* **Always use 4 spaces per indentation level.** Avoid mixing tabs and spaces.
* **Keep your indentation consistent.** If you use spaces in one part, use spaces everywhere.
* **Indent code inside blocks** such as `if`, `for`, `while`, `def`, and `class`.

#### 🔍 Example:

```python
# Correct indentation
def greet():
    name = "Alex"
    print("Hello,", name)

# Incorrect indentation (will cause an error)
def greet():
name = "Alex"
print("Hello,", name)
```

#### 📝 Tips:

* Most code editors (like VS Code) automatically indent for you.
* Turn on “show whitespace” in your editor to spot indentation errors.
* Do not use both tabs and spaces in the same file.


Sure! Here's a simple and beginner-friendly explanation about **commenting in Python**, written in a clear and human tone:

---

## 💬 Commenting in Python

Comments are notes you write in your code to explain what it does. Python ignores comments when running the program. They are just there to help you (and others) understand the code better.

#### 🔹 How to Write a Comment

In Python, comments start with a `#` symbol. Anything after the `#` on that line is ignored by Python.

```python
# This is a comment
print("Hello, world!")  # This prints a message
```

#### ✅ Why Use Comments?

* To describe what the code does
* To make your code easier to understand
* To remind yourself why you wrote something a certain way
* To temporarily disable a line without deleting it

#### 🔸 Multi-Line Comments (Tip)

Python does not have a special way for multi-line comments, but you can write several single-line comments in a row:

```python
# This program adds two numbers
# and prints the result
num1 = 5
num2 = 7
print(num1 + num2)
```

Or, you can use triple quotes `'''` or `"""` as a workaround, though it's mostly used for documentation:

```python
'''
This is not a true comment,
but Python will ignore it unless it's used as a docstring.
'''
```

#### 📝 Best Practices

* Keep comments short and clear
* Write comments **above** the code they describe
* Do not overuse comments, only write them where it helps understanding
* Update comments if you change your code


## 🛠 Built-in Functions

Python comes with many built-in functions. These are ready-to-use tools that help you perform common tasks.

Some popular ones:

* `print()` – displays text or values
* `type()` – checks the type of a variable
* `len()` – gives the length of a string or list
* `input()` – takes input from the user

```python
print("Hello!")
name = input("What is your name? ")
print("Welcome,", name)
```

Complete list of built-in functions can be found from [Python documentation](https://docs.python.org/3.9/library/functions.html)

## 📋 Data Types

Python has several basic data types:

* **String** (`str`) – text inside quotes
  Example: `"hello"`
* **Integer** (`int`) – whole numbers
  Example: `10`, `-5`
* **Float** (`float`) – numbers with decimals
  Example: `3.14`, `-0.5`
* **Boolean** (`bool`) – `True` or `False`

#### 🔍 Checking Data Types

Use the `type()` function to check what kind of data a variable holds.

```python
age = 20
print(type(age))  # Output: <class 'int'>
```

This is helpful when you are working with inputs or when debugging.

#### 🔄 Casting (Changing Data Types)

You can change one type of data into another using casting functions like:

* `int()` – converts to integer
* `float()` – converts to float
* `str()` – converts to string
* `bool()` – converts to boolean

```python
num = "5"
converted = int(num)
print(converted + 2)  # Output: 7
```

Always make sure the value can be converted. For example, `"hello"` cannot be turned into a number.


## 🧠 Quick Quiz

Test your understanding with these short questions. Try to answer them before checking the answers.

#### 1. Is Python case-sensitive?

a) Yes
b) No

#### 2. Which of these is a valid variable name?

a) `2score`
b) `user-name`
c) `total_amount`
d) `for`

#### 3. What will this code print?

```python
x = 7
print(type(x))
```

a) `<class 'str'>`
b) `<class 'float'>`
c) `<class 'int'>`
d) `<class 'bool'>`

#### 4. What is the output of this code?

```python
value = "10"
print(int(value) + 5)
```


## ✍️ Practice Section


Try these small exercises on your own. You can run them in the Python Shell or in a `.py` file using VS Code.

#### 🔸 Exercise 1: Create and Print Variables

* Create a variable called `first_name` and assign your name to it
* Create a variable called `age` and assign your age
* Print both values using `print()`

**Example Output:**

```
My name is Deepak and I am 25 years old.
```

#### 🔸 Exercise 2: Use type()

* Create three variables: one string, one integer, and one float
* Print the type of each using `type()`

#### 🔸 Exercise 3: Fix the Error

What’s wrong with this code? Fix it and run it.

```python
price = "20
print(price)
```

#### 🔸 Exercise 4: Casting Practice

* Take a string input from the user
* Convert it into an integer
* Add 10 and print the result


## 🧪 Exercises: Warm-Up with Variables

1. Inside your project folder, create a new file called `basics.py`.
   At the top of the file, write a comment like this:
   `# Learning Python: Variables, Types, and Simple Logic`

2. Declare the following variables with values of your choice:

   * `favorite_color` (string)
   * `birth_year` (integer)
   * `height_in_cm` (float)
   * `likes_pizza` (boolean)

3. Create a variable `full_sentence` that combines `favorite_color` and `likes_pizza` into a single string using the `+` operator. Print the result.

4. Declare `language`, `creator`, and `released_year` on the same line. Assign suitable values.

5. Assign your name to a variable called `nickname`. Use `print()` to show a welcome message using that name.

6. Create a variable `daily_temperature` and assign a float. Then declare another variable `rounded_temp` and convert it to an integer using `int()`.

7. Use the `type()` function to display the type of each variable you created above.

8. Create a string variable `movie_title`. Then use the `len()` function to print how many letters are in the movie title.

9. Set the following variables:

   ```python
   apples = 8
   oranges = 5
   ```

   Perform and store the results in new variables:

   * Total fruits
   * Difference in quantity
   * Ratio of apples to oranges (use float division)
   * Result of dividing apples by oranges with floor division
   * Whether the total number of fruits is even (use modulus `% 2`)

10. Create a variable `word = "true"` and convert it to a boolean using `bool()` and explain the result with a comment.

[<< 01_Installation](/01_installation.md) | [03_Data_Types >>](/03_Data_Types/02_data_types.md)
