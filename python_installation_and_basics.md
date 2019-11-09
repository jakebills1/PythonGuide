**Installing Python3 on windows 10**
1.  download python 3.8 installer from https://www.python.org/
2.  Run launcher, make sure to install launcher for all users, add to path, and disable path length limit
3.  run python app using start menu, and run pip -V to verify install
4.  install sublime text from https://www.sublimetext.com/
5.  Find sublime install folder, and add to path

**To open python REPL**
1. Open a command prompt: Start menu - cmd.exe
2. Type python, then press enter. You are now in the REPL (Read-Evaluate-Print Loop). type in any valid python expression and the interpreter will return the value to you
3. To exit, enter the command `exit()`

**Python programming basics**
 - Variables: a named reference to a value. any variable can store any value, and be reassigned to any other variable
	- `one = 1`
		- `<variable name> <assignment> <value>`
		- to assign value, use '='
	- `result = true`
		- true is a boolean, a true or false value
	- `name = "Hannah"`
		- a value wrapped in quotes is a string
- Control flow
	- conditional: test whether an expression is true or false, and performs an action as a result
		- comparing: `1 + 1 == 2 # true` 
			- to compare two sides of an expression, use '=='
			- to comment, type '#' then the comment you want to make. this will not be read as part of the program
		- if/else:

	        ```python
	        if (1 + 1 == 2)
		        print("this code will run because the condition in parentheses is true")
	        ```
			```python
			if(1 + 1 > 2)
				print("this code will not run, because the condition in parentheses is false")
			else
				print("this code will run, because no other condition was met")
			```
			```python
			if(1 + 1 > 2)
				print("this code will not run, because the condition in parentheses is false")
			elif(1 + 1 == 2)
				print("this code will run, because the if statement was not true")
			else
				print("this code will not run, because the elif (else if) statement was true")
			```
- Looping: perform an operation some number of times

            ```python
            num = 1 # num is a variable containing the number 1
            while (num <= 10) # while num is less than or equal to ten
            	print(num) # print num to the screen
            	num = num + 1 # assign the variable num to its previous value plus one
            ```
            
            ```python
            for i in range(1, 11) # i is some number in the range 1 - 11
            	print(i) # print i to screen
            ```