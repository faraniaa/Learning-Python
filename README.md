# Learning-Python
-----
This is what you can learn on this documentation :
* Type conversion in python
* Input and output
* Transformation
* Formatting String
* Operation (Operator and Operand)
* Conditional Expression
### Type Conversion in Python
-----
Using python, we can easily convert data into different type. In python, there are two types of type conversion.
1. Implicit Type Conversion </br>
Python automatically converts one data type to another data type. This process doesn’t need any user involvement. Implicit type conversion can’t work at string data type.
2. Explicit Type Conversion </br>
Users convert the data tyoe of an object to required data type, we can use the predefined functions like int(), float(), str(), etc. to perform explicit type conversion. </br>
This type of conversion is also called typecasting, because the user casts (changes) the data type of the objects. </br>
Here's the syntax :
``` 
<required_datatype>(expression)
``` 
### Input and Output
-----
1. Input Function</br>
The input() function is used to retrieve numeric data and retrieve text. In Python, it's enough to just use the input() function, because the raw_input() function is already combined there. </br>
#### How to Take Input from Keyboard
``` 
variable_name = input(" ")
``` 
2. Output Function
An output function is a function that an optimization function calls at each iteration of its algorithm. </br>
#### How to Take Output from Keyboard
To display text output, we use the print() function
``` 
print()
``` 
### Transformation
-----
In this section, we can learn :
#### Changing Uppercase and Lowercase
* Upper() </br>
Convert character/String from lowercase to uppercase. If the letter first big, then nothing will change. </br>
* Lower() </br>
The opposite of upper() . Used to convert characters/strings from letters uppercase to lowercase. </br>
#### A Beginning and an End
Method : </br>
* rstrip() : This method will remove the whitespace to the right of the string or the end strings.
* lstrip() : Useful for removing whitespace on the left or the beginning of a string.
* strip() : Will remove whitespace at the beginning or end of the string.
* startswith() : This method will return True if the string starts with the word the specified prefix we want, otherwise it returns False.
* endswith() : As opposed to startswith() , this method returns True if the string ends with the specified suffix we want, otherwise it will returns False value. With this method, you can perform string comparisons in the form of a beginning or a suffix only, so there is no need to separate the strings and use the equal to operator (==).
#### Splitting and Concatenating String
Method :
* join() : The method used to concatenate a number of string. The string with the join() operation will be inserted between the string in the parameter.
* split() : Method that splits substrings based on a specified delimiter (default is whitespace, tab, or newline).
#### Replacing String Elements
Method :
* replace() : This method can return a new string in the condition that the substring has been replaced with the entered parameter.
#### String Check
Method :
* isupper() : This function will return True if all the letters in the string is uppercase, and will return False if there is only one lowercase letter in in that string.
* islower() : This function is opposite of isupper() method, this method will return value True if all letters in the string are lowercase, and will return the value False if there is only one uppercase letter in the string.
* isalpha() : This method will return True if all characters in string are letters of the alphabet. Otherwise it will return False.
* isalnum() : This method will return True if the character in the string is alphanumeric, only letters or only numbers or both. If not then will returns False value.
* isdecimal() : This method will return True if the characters in the string are only contains numeric, otherwise it returns False.
* isspace() : This method will return True if the string contains only whitespace, such as space, tab, newline or other whitespace characters. If not then will return False.
* istitle() : This method will return True if the string contains capital letters on each word and then followed by a lowercase letter, otherwise it will return the value false.

### Formatting String
-----
In this section, we can learn 5 formatting string in python :
1. Zfill() </br>
\- A method that can add a numeric value of 0 to the left of a number or string </br>
\- Can be applied to invoice numbers or queue numbers </br>
\- The number of characters must be less than or equal to the zfill value </br>
2. Text align right </br>
\- This method will add a space to the string to make it match </br>
\- The parameter is an integer which is the overall length of the text (not the number of spaces added) </br>
Here's how to use text align right on Python </br>
``` 
text.rjust()
``` 
3. Text align left </br>
\- This method will add a space to the string to make it match </br>
\- The parameter is an integer which is the overall length of the text (not the number of spaces added) </br>
Here's how to use text align left on Python </br>
``` 
text.ljust()
``` 
4. Text align center </br>
\- This method will add a space to the string to make it match </br>
\- The parameter is an integer which is the overall length of the text (not the number of spaces added) </br>
Here's how to use text align left on Python </br>
``` 
text.center()
``` 
5. String Literals </br>
Generally strings are written easily in python, enclosed in single quotes. However, under certain conditions, it takes a single quote in the middle of the string. </br>
The escape character i.e. backslash allows you to enter the 'and' character in the string part. </br>
Here's how to use string literals on Python </br>
``` 
A = ("List to buy : \n \-Soy Milk \n \-Nuggets)
``` 
### Operation
-----
#### Operation in List, Set, and String
* len() : will returns the length of an object
* min() : return the lowest value
* max() : return the highest value
* count() : data occurens
* Merging (+) and replication (*)
``` 
a = [1, 2, 3]
b = ['p', 'y', 't', 'h', 'o', 'n']
a+b
a*2
``` 
* range() : usually used for loop processes. We can use the range() in 3 ways (parameters). And it will look similar to Slicing data on a List
* Multiple Value using List [ ] : using new variable to assign a list index
* sort() : sorting a value from numerical or string
### Python Operators
Operators are used to perform operations on variables and values. </br>
#### Python Arithmatics Operation
Arithmetic operators are used with numeric values to perform common mathematical operations.
* Addition (+)
``` print(x+y)``` 
* Substraction (-)
``` print(x-y)``` 
* Multiplication (*)
``` print(x*y)``` 
* Division (/)
``` print(x/y)``` 
* Modulus (%)
``` print(x%y)``` 
* Exponentiation (\**)
``` print(x**y)``` 
* Floor Division (//)
``` print(x//y)``` </br>
#### Python Assignment Operators
Assignment operators are used to assign values to variables. also we can using our variable as an operand. </br>
#### Python Comparison Operators
Comparison operators are used to compare two values. This operators will return True or False
* equal (==)
* not equal (!=)
* less than (<) and less than or equal to (<=)
* greater than (>) and greater than or equal to (>=) </br>
#### Python Logical Operators
Logical operators are used to combine conditional statements. also we known as BOOLEAN OPERATORS. So the return will be True or False
* and ( Return True if both statements are true )
* or ( Return True if one of statements is true )
* not (Reverse the result) </br>
#### Python Identity Operators
Identity operators are used to compare the objects, not if they are equal, but if they are actually the same object.
* is ( Returns True if both variables are the same object )
* is not (Returns True if both variables are not the same object) </br>
#### Python Membership Operators
Membership operators are used to test if a sequence is presented in an object.
* in
* not in </br>

### Conditional Expression
-----
#### if Statement
There is only one condition or expression, where if the condition is True , it will return the specified statement or value or output.</br>
In its simplest form, it looks like this:
```
if <expr>: 
  <statement>
```
#### else Statement
There are two conditions, where if the first condition is True, it will return the specified value or output in that condition. and if the value is False it will output another value or find another alternative.</br>
In its simplest form, it looks like this:
```
if <expr>: 
  <statement>
else :
  <statement2>
```
#### elif Statement
There are more than two conditions or alternatives, the statement will be executed if one of the conditions is True. If it does not get a True value then it will go to the last option which is in else. </br>
In its simplest form, it looks like this:
```
if <expr>:
    <statement>
elif <expr2>:
    <statement2>
elif <expr3>:
    <statement3>
........
else:
    <statement_n>
```

