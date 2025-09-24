# What is a variable ?

Variable is a container for your stored data . When ever you assign a value to variable computer reserves some space for it in its memory  and inside that space the value is stored .
To use a variable we have to create it , and it requires some steps  , while you are learning python so it is quiet easy to do this job 

variable name = value 
x = 5
# but while naming a variable you have to be carefull of some steps :

01 - Must start with an alphabet or underscore 
02 - Can contain only letters , alphabets and underscores 
03 - Can not use reserved words 
04 - Spaces in between are not allowed
05 - Case sensitive 

# How to print a Variable ?

printing a varaiable is not same as printing a common line , you have to just not write your variable name in " " unless you want it to be write in " " 
var = 23
print ( var )
if you want to show your variable in " " , then simply use string methood ;
print ( f ' " { var} " ' )

# Data types in Python 

01 - Numbers → int, float, complex
02 - Text → str
03 - Sequences → list, tuple, range
04 - Mapping → dict
05 - Sets → set, frozenset
06 - Boolean → bool
07 - Binary → bytes, bytearray, memoryview
08 - Special → NoneType

# How input and output functions work ? 
 
 when you want to print some line ;
print ( "that line ")
when you wnant to print var ;
print ( var_name )
when you wnat to print both ;
print (f' hello {var_name} is on call ' )

when you want to take simple input ;
var_name = input( " enter your name " )
when you want to specify datatype also while taking input ;
var_name = int ( input (" your age " ))
