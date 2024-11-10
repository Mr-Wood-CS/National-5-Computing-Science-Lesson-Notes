# Conditional Loops (while)

## Explanation

A conditional loop (__in Python, a while loop__) repeats only while a condition is true. 

A conditional loop is like a combination of a fixed loop and an if statement and you can use all of the same conditions in a while loop that you would in an if statement.

> In this example, the user is asked to enter a number. 

> If the number is more than 100, part of the program repeats, asking them to enter the number again. 

> It only repeats while their input is more than 100. Once that condition is met, the loop stops repeating and the program continues:

!!! example

	```python linenums="1"
		# Initialise the variable
		mynumber = 0
		
		# Ask the user to enter a number
		mynumber = int(input("Please enter a number"))
		
		# Example of a while loop
		while mynumber > 100:
			print("That number is too big!")
			mynumber = int(input("Please enter a number"))
	```

!!! warning "don’t get stuck in an __infinite loop__"

	Make sure that your condition will always end.
	
	For example, this loop would never end as 100 is always more than 5, so the loop will continue running indefinitely.

		```python linenums="1"
			while 100 > 5:
				print("One hundred is still more than five")
	        ```

