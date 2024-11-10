# Pre-Defined Functions

## Explanation

Pre-defined functions are built-in to Python. This saves you “reinventing the wheel” each time you use them.

When you use a pre-defined function, you pass one or more parameters. 

__The parameter is the part in brackets.__

!!! example

	```python linenums="1"
		pi = round(3.14159265)
	```
There are three pre-defined functions that you must know for National 5: 

* Random
  
* Round

* Length

## Random Number

Something that is random is open to chance - like rolling dice, or tossing a coin.

Before we use a random number, we have to put this line at the top of the program:

!!! example

	```python linenums="1"
		# This program is going to use random numbers
		import random
	```

Random will always returns an integer (a whole number) and will only generate a random number that is between two parameters:

!!! example

	```python linenums="1"
		# Generate a random number from 1 to 6
		dice = random.randint(1, 6)
	```

The code above will generate a number that could be either 1, 2, 3, 4, 5 or 6.

Complete example:

!!! example "The Random Number Game"

	```python linenums="1"
	
		# Add the random module
		import random
		
		# Ask the user to enter a number
		guess = int(input("What is your guess?"))
		
		target = random.randint(1, 10)
  
		if guess == target:
			print("Well done, you guessed correctly.")
		else:
			print("Sorry, you guessed wrongly")
	```
## Length

The length function, shortened to len() returns the length - the number of characters - in a string.

__For example, len(“hello”) is 5, and len(“abc”) is 3:__

This example calculates the length of a word, stores it in a variable called “how_long”, and displays it on the screen.

!!! example

	```python linenums="1"
	
		# Stores and displays how many characters are in the word “hello”
		how_long = len("hello")
		print(how_long)

	```

You could also use len() to ask the user to enter a password, and tell them whether their password is long enough:

# Ask the user to enter a password
passwd = input("Please enter your password")

# The password must be at least 6 characters long
if len(passwd) > 6:
    print("Your password is long enough")
else:
    print("Your password is NOT long enough")
!!! example

	```python linenums="1"
	
		# Ask the user to enter their password
		passwd = input("Please enter your password")
		
		# The password must be at least 6 characters long
		if len(passwd) > 6:
		    print("Your password is long enough")
		else:
		    print("Your password is NOT long enough")

	```    

__This problem could be refined further by using a loop and asking the user to keep entering their password until it is valid.__
		 
