# 1.Number, String and Boolean
Built-in data types in Python 3:
1. Numbers
2.	Strings
3.	Boolean

## 1.Numbers
Numbers Numeric types in Python are divided into 3: int, float, complex.The difference between an integer and a float is a dot (decimal points).Complex numbers are used for imaginary numbers and must use the variable j.

## 2.Imaginary Numbers
Because Python is also widely used by mathematicians, the number type in Python also supports imaginary numbers and complex numbers. Complex number values are written in the formulation x+yj, ie the x part is a real number and y is an imaginary number. An example is as follows:

## 3.String
A string is a sequence of unicode characters declared in single or double quotes. Strings > 1 line can be marked with either triples or double quotes ("" or """)

## 4.Write I'm escape character
The use of Escape Character is used to enter illegal characters into a string using the backslash \ followed by the character you want to input. Example:

## 5. Boolean Using == because if using = is like input to a variable
Bool/Boolean is an instance of an integer (integer or int) which has only two constant values: True and False.


# 2.List 
## List
List is a type of ordered sequence data collection and is one of the variables that is often used in Python. Similar, but not the same as arrays in other programming languages. The difference is, List elements in Python do not have to have the same data type. easy with square brackets and comma separated elements.List data types do not have to be the same, and lists collect data sequentially. List data types start from index 0.Every data in it can be accessed with an index starting from 0.Using the sign (-) means searching from behind the list

## List 3 Parameters
*	a = [5,6.7,'eight']
*	Using 3 parameters a[x:y:z]
*	x = starting from what index list, each list starting from 0
*	y = Number of characters to output
*	z = Like multiples, if written 2 then each index is a multiple of 2

## Len (Count Number of Characters)
## Change the character at an index position
## Multiple Ways to Add Character

## Append (x)
Adds a single element x to the end of a list
## Extend (L)
Merge another list L to the End
## Insert
insert element x at position i

## Multiple Ways to Delete Characters
Del 
Del is used to delete according to index
Remove
Remove is used to remove the value found from the initial index
Pop
Pop is used to delete the last index

## Index
Index is used to find the index to how many characters x

## Count
Count is used to count the number of x characters in the array

## Sort
* Sort the list
* Sort with Reverse

## Reverse
Displays from the last index but not sorted

# 3.Slicing String
Because strings are similar to lists, the slicing operator [] can also be used on strings to retrieve their contents or even substrings. A complete string is mutable (can be changed), but its elements are immutable (cannot be changed).

# 4.Tuple
A tuple is a type of list whose elements cannot be changed. Tuples are generally used for write-on data and can be executed faster. Tuples are defined by brackets and elements separated by commas. Like lists, we can do slicing, but on tuples we can't make changes
## Tuple 1 Parameters
## Tuple 2 Parameters
## Tuple 3 Parameters

# 5.Set
Set is a collection of unique and unordered items (unordered collection). It is defined with kurawai and the elements are separated by commas. In Set we can do union and Intersection. At the same time, it will automatically delete duplicate data.
* Union
* Intersection

# 6. Dictionary
Dictionary in Python is a collection of key-value pairs (pairs of key-value) that are not sequential. Dictionaries can be used to store small to large data. To access the data, we must know the key (key). In Python, dictionaries are defined with curly braces. and the following additional definitions:
1. Each key-value pair element is separated by a comma(,).
2. Key and Value are separated by a colon (;).
3. Key and Value can be any type of variable/object
Dictionary is not included in the Sequences implementation so it cannot be called by index order. For example, in the following example, we tried to try with index 0, but it produces error(KeyError) because there is no key (key) 0

# 7. Transforming Numbers, Characters and Strings
Both of these methods, both Upper() and Lower() are python's built-in methods that are used to handle string operations.If there are non-letter characters (such as symbols or numbers) that do not have capital options, they are not changed.

## Upper
Upper() converts a character or string from lowercase to uppercase.But if the original letter is uppercase, then the letter does not change

## Lower
Lower() converts a character or string from uppercase to lowercase.But if the original letter is lowercase, then the letter does not change

## Strip,Lstrip and Rstrip
### rstrip()
rstrip() will remove the whitespace to the right of the string or the end of the string

###lstrip()
lstrip() is used to remove whitespace to the left or the beginning of the string

### strip ()
strip() will remove whitespace at the beginning or end of the string.Strips can also be used to delete 1 word data from the beginning of a sentence

### Startswith()
The startswith() method will return True if the string starts with the specified prefix we want, otherwise it will return false.

### Endswith
The endswith() method is the opposite of the startswith() method. This method will return True if the string ends with the specified suffix we want, otherwise it will return False.

# 8.Conversion between data types
Conversion (conversion,cast) between data types
We can convert the default data type by using the standard type conversion function, for example: int(),float(),str(),etc.Converting float to int will be floor/truncating or remove the trailing comma.

# 9.Input Output in Python
## Variables
A variable is a place (in computer memory) to store values of a certain data type. To assign a value to a variable, we use the "=" operator, between the variable name and the value we want to store.

## Print
The print() function is a direct output way to the console/screen
Entering a variable value in a string To enter the value of a variable in a string. Python has several ways
1. Directly concatenate variables in the print() statement.
2. To display text (string), can use the format string mechanism.
3. Using "%" operator added with "Argument Specifiers"
Some examples of commonly used specifer arguments:
* %s - String
* %d - Integers
* %f - Decimal Number

## Input()
To allow the user to provide input to your program, use the input() function, where the argument in brackets () is the text you want to display (prompt) and the variable before the equal sign (=) is the result holder of user input.By default, the input from the user is a string.Input can change from string to int with method.

# 10.Replacing String Elements
## Replace
The Replace() method can also return a new string if the substring has been replaced by the entered parameter

## Replace() 3 Parameters
The third parameter in replace can be filled with the number of substrings you want to replace

# 11.String Check
## String Check
In the string checking category it will check the boolean of a string.

## isupper()
The isupper() method returns True if all letters in the string are uppercase and returns False if there is only one lowercase letter in the string.
## islowers
The islower() method is the opposite of the isupper() method, this method will return True if all letters in the string are lowercase and will return False if there is only one uppercase letter in the string.

We can perform operations on the result of the operation (chain of methods)

## Isalpha ()
This method will return True if all characters in the string are letters of the alphabet, if there are numeric or spaces it will return False.

## Isalnum ()
This method will return True if all characters in the string are alphabetic or numeric, if there are spaces it will return False.

## Isdecimal ()
This method will return True if all characters in the string are numeric, if there are spaces or alphabet letters it will return False.

## Isspace ()
This method will return True if the string contains only whitespace characters, such as spaces, tabs, newlines or other whitespace characters. Otherwise, it will return False.

## Istitle ()
This method will return True if the string contains a capital letter in each word and continues with lowercase letters and so on, otherwise it will return a value of False

# 12.Formatting on String
## zfill()
*	A method that can add a numeric value of 0 to the left of a number or string using the zfill() method
*	The use of this zfill() method can be applied to invoice numbers or queue numbers.
*	The number of characters must be less than or equal to the zfill value.

## Rjust (Align right)
## Ljust (Align left)
## Center (Align the center)

