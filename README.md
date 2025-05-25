# pythonfiles-2
# Python Functions
Functions in Python are blocks of reusable code that perform a specific task. They help make programs modular, readable, and easier to maintain.
#----------------------------------------------------------------------
# 🔧 Defining a Function

def function_name(parameters):
    # code block
    return result
def: Keyword used to define a function.

function_name: Name of the function.

parameters: Optional inputs passed to the function.

return: Sends back the result (optional).
#----------------------------------------------------------------------
Example:

def greet(name):
    return "Hello, " + name

print(greet("Alice"))  # Output: Hello, Alice
#----------------------------------------------------------------------
# 📥 Parameters and 📤 Return Values

Functions can have:
No parameters
One or more parameters
Return values or no return
#----------------------------------------------------------------------
def add(a, b):
    return a + b
#----------------------------------------------------------------------
# 🧰 Default Parameters

def gre(name="Guest"):
    print("Hello", name)

gre()        # Hello Guest
gre("John")  # Hello John
#----------------------------------------------------------------------
# 🔁 Function with Loops

def print_numbers(n):
    for i in range(n):
        print(i)
#----------------------------------------------------------------------
🧠 Why Use Functions?
Avoid repetition
Break down large problems
Improve readability
Enable code reuse