# Scientific-computing-with-Python-summary
#python is used in many feilds like data science , machine learning, web development, scripting and automation , etc. 

#python is widely used in DevOps for writing CI/CD scripts , one of Python's biggest strengths is automation

#in web → Django ,FastAPI , Flask 

#DS/ ML → Numpy / Pandas 

#embedded systaems & IoT → Raspberry Pi & compatible boards



#To declare variables in Python, you assign a value to an identifier with the assignment (`=`) operator. 

#- just remember that Python is case-sensitive so the lowercase letter different from the uppercase letter
#- the rules of naming the variables are very important and it should be descriptive



name = 'Jhon Doe'# string 

age =25 #integer 
#the way to output data is by using (print) function
print ('Hello World!') 
# we can make multiple values 
print ('My favorite colors are ','blue','green','red')
#Python automatically adds a space between each item when you separate them with commas



# A data type describes the kind of value a variable holds
my_integer_var = 10
print('Integer:', my_integer_var)
#Integer: A whole number without decimals
my_float_var = 4.50
print('Float:', my_float_var) 
#Float: A number with a decimal point
my_string_var = 'hello'
print('String:', my_string_var)
#String: A sequence of characters enclosed in single or double quotation marks
my_boolean_var = True
print('Boolean:', my_boolean_var)
#Boolean: A true or false type
my_set_var = {7, 5, 8}
print('Set:', my_set_var) 
#Set: An unordered collection of unique elements
my_dictionary_var = {'name': 'Alice', 'age': 25}
print('Dictionary:', my_dictionary_var)
#Dictionary: A collection of key-value pairs enclosed in curly braces
my_tuple_var = (7, 5, 8)
print('Tuple:', my_tuple_var)
# Tuple: An immutable ordered collection, enclosed in brackets and we can't add,delete or change the element 


# the built-in (isinstance) function checks if the variable matches the datatype or not 
isinstance(42, int) # True
isinstance('John Doe', int) # False


#To get the data type of a variable, you can use the type() function
my_var_1 = 'Hello world'
my_var_2 = 21
print(type(my_var_1)) 
