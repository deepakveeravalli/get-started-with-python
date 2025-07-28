# 📘 Introduction to Python

Python is a popular programming language known for its simple and readable syntax. It is often the first language people learn because it feels close to everyday English and is easy to write and understand. Python can be used to build websites, automate tasks, analyze data, create software, and much more. It works across different platforms and has a large community that supports learning and problem-solving. Whether you are just starting out or looking to explore new ideas, Python offers a smooth and friendly way to begin your programming journey. It grows with you as you learn.


## 🛠 Installing Python

Before you start writing Python code, you need to install Python on your computer. The process is simple and takes just a few minutes.

#### 🔹 Step 1: Download Python

Go to the official Python website: [https://www.python.org/downloads](https://www.python.org/downloads)
Click on the download button for your operating system (Windows, macOS, or Linux). The latest stable version is usually recommended.

#### 🔹 Step 2: Run the Installer

After downloading, open the installer.
For Windows users, **make sure to check the box that says “Add Python to PATH”** before clicking “Install Now.” This step helps you run Python from any folder using the command prompt.

#### 🔹 Step 3: Verify the Installation

Once installed, open your terminal or command prompt and type:

```bash
python3 --version
```

You should see the version number printed, which means Python is ready to use. As you can see below, I've 3.13.5 version installed on my machine.

<img width="639" height="153" alt="image" src="https://github.com/user-attachments/assets/39f479b6-361c-4e3f-90e3-d57c9cdc47fd" />


## 🐚 Getting Started with the Python Interpreter

The **Python Interpreter** is a simple way to write and run Python code directly. It is often the first tool people use to test ideas or learn the basics.
It is an interactive shell that lets you type and run Python code one line at a time. It works by interpreting your commands immediately, which means it reads and runs the code as you type it. You can open the shell by typing `python` in your terminal after installation. When you see `>>>`, it means Python is ready. You can try math, print messages, or test small bits of code. It is a great way to learn and experiment. When you are done, type `exit()` to close the shell. No files are needed to get started.

#### 🔹 How to Open It

After installing Python, open your terminal or command prompt and type:

```python
python3
```

This will start the Python Shell. You will see something like this:

```
>>>
```

The `>>>` prompt means Python is ready for you to type a command.

#### 🔹 Try It Out

Type the following and press Enter:

```python
print("Hello, Python!")
```

You should see:

```
Hello, Python!
```

You just ran your first Python command in the shell.

<img width="705" height="137" alt="image" src="https://github.com/user-attachments/assets/0eb23394-5dba-4384-8b49-689406d8b7e2" />

>`Let us do some basic mathematical (addition, subtraction, multiplication, division, modulus, exponential) and comparision operations in Python Interactive shell.`

    5 + 4 is 9
    5 - 4 is 1
    5 * 4 is 20
    5 / 4 is 1.25
    5 ** 2 is 25 (exponential)
    5 > 4 is True
    5 < 4 is False
    5 == 5 is True

<img width="710" height="326" alt="image" src="https://github.com/user-attachments/assets/70bc83cf-6eee-42e7-90d8-bb7f194d629e" />

#### 🛑 **Syntax Error**
A syntax error happens when you write code that Python doesn't understand. It's like making a grammar mistake in a sentence. If something is missing or typed incorrectly, Python will stop and show an error message.

```python
2 + # don't add second value, instead hit enter.
```
<img width="707" height="138" alt="image" src="https://github.com/user-attachments/assets/1e8d0453-6475-480f-8c8b-f151f735d5a7" />

As you can see from the above, the interactive shell displayed and error: `Syntax Error: invalid syntax`

#### 🔹 To Exit the Shell

To close the Python Shell, type:

```python
exit()
```

Or press `Ctrl + Z` on Windows or `Ctrl + D` on macOS/Linux and then press Enter.


## 🧑‍💻 Installing VS Code (Visual Studio Code)

While the Python Shell is great for quick tests or learning simple commands, it is not ideal for writing longer programs. An IDE (Integrated Development Environment) like VS Code makes it easier to write, edit, and organize code in files. It highlights mistakes, suggests code completions, and lets you run entire programs with one click.

**VS Code** is a free and lightweight code editor that works well with Python. It makes writing and testing code easier with features like syntax highlighting, extensions, and auto-complete.

#### 🔹 Step 1: Download VS Code

Go to the official website: [https://code.visualstudio.com](https://code.visualstudio.com)
Click the **Download** button for your operating system (Windows, macOS, or Linux).

#### 🔹 Step 2: Install the Editor

Open the downloaded file and follow the setup instructions.

#### 🔹 Step 3: Install the Python Extension

After installing VS Code, open it.
Click on the **Extensions** icon on the left sidebar (press `Cmd+Shift+X` on windows (or) press `Ctrl+Shift+X` on windows).
Search for **"Python"** and install the one by Microsoft. This helps you run and debug Python code smoothly.

### ✅ You’re Ready!

Now you can open any `.py` file or create a new one and start coding in a clean, beginner-friendly environment.

[02_Fundamentals >>](/02_Fundamentals/fundamentals.md)
