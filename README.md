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
##### rstrip()
-----
This method will remove the whitespace to the right of the string or the end strings.
##### lstrip()
-----
Useful for removing whitespace on the left or the beginning of a string.
##### strip()
-----
Will remove whitespace at the beginning or end of the string.
##### startswith()
-----
This method will return True if the string starts with the word the specified prefix we want, otherwise it returns False.
##### endswith()
-----
As opposed to startswith() , this method returns True if the string ends with the specified suffix we want, otherwise it will returns False value. With this method, you can perform string comparisons in the form of a beginning or a suffix only, so there is no need to separate the strings and use the equal to operator (==).
#### Splitting and Concatenating String
Method :
##### join()
-----
The method used to concatenate a number of string. The string with the join() operation will be inserted between the string in the parameter.
##### split()
-----
Method that splits substrings based on a specified delimiter (default is whitespace, tab, or newline).
####
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
