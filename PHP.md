#PHP Basics

* ###Variables

	- A valid variable name starts with a letter or underscore, followed by any number of letters, numbers, or underscores.
	- Variables can hold different data types.
	- You can assign the results of a statement to a variable using the assignment operator (=)
	- You can use variables like the data type that it contains

* ###Type Juggling
	
	- PHP can perform type juggling
	- Allows a variable to change its value and datatype
	- The datatype of the variable depends on the value that it holds
	- You can use parenthesis in var_dump() to change a variables type **(casting)**
		
		ex. 

			   php > $some_var = 1;
			   php > var_dump($some_var);
			   int(1)

			   php > ver_dump((bool) $some_var);
			   bool(true)

##Data Types

* ###Strings

	- echo outputs a string
	- They can be made with either double "" or '' single quotes
	- When using single quotes, PHP does not evaluate what is in the string
		+ **Concatenation** is a common way to join strings together when you need to evaluate variables and are using single quotes.
		+ **Escape Characters** are used to escape parsing in strings with words containing a single quote. (It's) => (It\'s)

* ###Boolean

	- Purely logical
	- Can hold only one of two values TRUE and FALSE
	- var_dump() can easily output a boolean variables info where an "echo" can't

* ###Integer
	- Can be whole numbers, positive or negative
	- An integers default is base10 (or decimal) but hexadecimal and binary can also be used. Hex values can be stored in variables but var_dump will still output its decimal value
s
* ###Float
	- Also known as doubles or floating point numbers
	- These numbers have a decimal point

* ###Array

* ###Object

* ###Resource

* ###NULL