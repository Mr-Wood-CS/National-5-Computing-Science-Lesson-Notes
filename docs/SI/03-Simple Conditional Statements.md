# Variables and Data Types

## What are Variables?

A variable is something that can be assigned a value.

!!! example
	```Python
	x = 5
	y = 2
	```
You will already have used similar in **Maths**. What is x + y? (the answer is 7)

**In computing however, we usually give them a longer (more meaningful) name, such as:**

!!! example
	```Python
	age = 15
	name = "Bob"
	email = "bob@gmail.com"
	```
	
## Python Variable Naming Rules

- A variable name must start with a letter or the underscore character
- A variable name cannot start with a number
- A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
- Variable names are case-sensitive (age, Age and AGE are three different variables)
- A variable name cannot be any of the **Python keywords**.

and although this one is not a rule....

- It is important to use **meaningful** or **sensible** variable names. 

## Types of Variables

In programming variables have a particular type and for National 5 there are five data types that you need to know:

| Data Type   | Description                                  |
| :---------: | :-------------------------------------------:|
| Integer     | Whole number: 12, -50, 100                   |
| Real number | With a decimal point: 22.5, 0.001            |
| String      | Words and symbols: hello, abc123             |
| Character   | A single letter, digit or symbol: a, Z, $, # |
| Boolean     | True (1) or False (0)                        |

!!! warning

    Once a variable has been set up with a particular type, you can only assign it data of that type.


!!! example
	```Python
	# This is an integer
	myage = int(15)

	# This is a real number
	price = float(0.99)

	# This is a string
	faveSubject = str("Computing")

	# This is a character
	firstInitial = char("F")

	# This is a Boolean
	isStudent = bool(1)
	```

## Calculations

Python programs will often carry out calculations with operators. The result is usually stored in a variable:

!!! example
```Python
num1 = 5
num2 = 7
sum = num1 + num2
```

You can use the following operators:

!!! example
	```Python
	# Three variables
	num1 = 5
	num2 = 7
	sum = 0.0

	# Addition
	sum = num1 + num2

	# Subtraction
	sum = num1 - num2

	# Division
	sum = num1 / num2

	# Multiplication
	sum = num1 * num2

	# Raise to a power
	sum = num1 ** num2

	#Note that “raising to the power” means, for example, num1**num2. 

	#To square or cube a number, you would say:
	square = num1 ** 2
	cube = num1 ** 3
	```

## String Concatenation

String concatenation is the term used when **joining** two strings.

!!! example
	```Python
	word1 = “Hello”
	word2 = “World”

	sentence = word1 + word2
	```

!!! tip

    The example above doesn’t include a space, you would have to add a space to the end of **“Hello”** or the beginning of **“World”**. 


