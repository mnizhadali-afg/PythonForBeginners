# Welcome to Python for Beginners

In this repository, you will learn the basics about Python programming language.

## Python is used in:

- [Artificial Intelligence](https://en.wikipedia.org/wiki/Artificial_intelligence)
- [Robotics](https://en.wikipedia.org/wiki/robotics)
- Servers Configuration and Management
- Mobile, Desktop and Web App development
- [and more...](https://en.wikipedia.org/wiki/Python_(programming_language))

## Setting up the environment
### Download Python
You can download the latest version of Python installer from [here](https://www.python.org/downloads/). 
Just follow all the steps and finish the installation. Once the installation finished, open up the _IDLE_ Python's editor and write your code. After wrting the code, save the file with any name, but the extension should be `.py`, then press `F5` to run your code.

### Wrting (Hello, World!)
Let's go deeper on the concepts. We start with the legacy **Hello, World!** program.
The syntax in Python are very easy to follow. Let's write our first program.

```
print('Hello, World!')
```

### Hint
Python don't use the semiconol `;`, so be happy with that :)

---

## Variable
Variable is used to store a data. It's in computer's memory and when you need it, you can use it. Then, inside the `print` statement, you can put a comma and then use the variable name, to show its value on the console.
```
name = 'Ali'
print('Hello, ' , name)

```
### Variable naming rules
When creating variables, you must follow some rules to declare the right variable. Here are the basic rules:
- Variable names contains:
  - letters
  - numbers
  - characters
- and starts with only:
  - underscore
  - letters
  - but not **numbers**
- Space is not allowed, if a variable name is combined of two words, you can use underscore instead.
- Don't use Python keywords like (print, def, and, etc.)
- It should be short and descriptive

## Data Types
- **String**: As other programming languages, you can create textual information in Python. To support `string`, you can use different symbols. Two symbols used for string are: `''` (single-quout) and `""` (double-quote). You created string in last example.
- **Numbers**: Python supports both decimal and non-decimal numbers. After assigning the value for the variable, Python decides which type of number is assigned to the variable. Don't worry, he is so SMART :)

### Example (String)
```
first_name = "Ali"
last_name = "Mousavi Nizhad"
print(first_name, last_name)
```

### Example (Number)
```
first_number = 12
second_number = 25.12
sum = first_number + second_number
print(sum)
```