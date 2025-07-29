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

#### **Valid**
* A variable name must start with a letter or the underscore character
  Example: `firstname`, `first_name`, `age`, `_if` # reserved word as a variable
* Use **lowercase letters** and words separated by underscores (snake_case)
  Example: `user_name`, `total_amount`
* A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )

#### **Invalid**
* Names **cannot start with a number**
  `2name` → Invalid
* Avoid using spaces or special symbols in variable names
* Do not use Python keywords like `class`, `print`, or `for` as variable names

Choose meaningful names that explain what the variable holds.


## 📦 Variables

Variables store values in computer memory. You don’t need to declare their type, just assign a value and Python will figure it out.

```python
name = "Emily"
age = 25
is_student = True
```

You can change a variable’s value later in the program.


## 📏 Best Practices for Indentation in Python

In Python, **indentation is not optional—it is required**. It tells Python which lines of code belong together. If the indentation is incorrect, your code will not run. Indentation means leaving spaces at the beginning of a line to show that it is inside a block, like a loop or a function. In most cases, you press the **Tab** key or type **4 spaces**.

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

a) 15
b) "105"
c) Error
d) 10

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
