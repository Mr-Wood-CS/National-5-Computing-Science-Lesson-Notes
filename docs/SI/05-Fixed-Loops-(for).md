# Fixed Loops (for)

## Explanation

So far, when ever we have wanted to output a word multiple times, we have always wrote a new print statement for each line.

!!! example

	```python linenums=1
		print("Hello world")
		print("Hello world")
		print("Hello world")
		print("Hello world")
		print("Hello world")
		print("Hello world")
		print("Hello world")
		print("Hello world")
		print("Hello world")
 	```

__This is very inefficient.__

Suppose we wanted to change the message - we’d have to go back and change every line individually, taking up time. 

We would also be much more likely to make a mistake.

To fix this we could instead, use a fixed loop.

A fixed loop is a loop that repeats a certain (fixed) number of times. 

This example is exactly the same as the code above, but with much less code.

!!! example

	```python linenums=1
		for loop in range(1, 10):
			print(“Hello world”)
 	```
  
The word loop is a variable that we could use within our code. It is called the loop counter, because it counts how many times the loop has run so far. 

We could use any other variable name, say bananas:

!!! example

	```python linenums=1
		for bananas in range(0, 8):
			print(bananas)
 	```

This (more complicated) example is a bitmore complicated as it asks the user to enter any number,ten times (0-9). 

Each time the loop repeats, it asks for another number, and adds it to its running total:

!!! example

	```python linenums=1
		# Example with a running total
		total = 0
		
		for loop in range(0, 10):
			number = int(input("Please enter a number"))
			total = total + number
		
		# Show total once the loop is done
		print(total)
 	```



