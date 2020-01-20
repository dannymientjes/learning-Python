# learning-Python
learning Python
Data Types

So, we got about 8 data types in Python (there are more, but for now, we stick to these only)
  Boolian
  Integer
  Float
  String
  List
  Tuple
  Set
  Dictionary

All of these data-types can be assigned to a "variable"
For example:
a=4
or a=[4,6,"s",9]

The List, Tuple, Set, and Dictionary can have multiple items inside.
And they can even contain List, Tuple, Set, and Dictionary in themselves.
 
For example:[1,2,3,4,(3,8,1),6,9]
So in this example list you find: integers and a Tuple
As far as I know the possibilities are unlimited. 


bool   = Boolian      example: True
bool   = Boolian      example: False
int    = Integer      example: 2
float  = Float        example: 4.67
str    = String       example: "hello"
list   = List         example: [1, 2, 3]
tuple  = Tuple        example: (1, 2, 3)
set    = Set          example: {1, 2, 3}
dict   = Dictionary  example: {1: 'y', 2: 'd', 3: 'f', 4: 'L'}

A Boolian can only be True or False
An Integer is a whole number
A Float is a number like 3.666
A String is text, it istext between the " "
A List is anything between the [  ] and separated with a comma, and it can contain every data-type from the list above.
A Tuple is anything between the (  ) Just like a list, but items can not be added or deleted from a tuple.
A Set is anything between the {  } like a list, but it will not contain any items more than ones.
A dictionary is like a Set, between the { } you will find the "key" and "value" separated by a colon. it will not contain any key more than ones.
example: {key1: 'y', key2: 'd', key3: 'f',key4: 'L'}


When you have a bug in your code, or something is not working properly it very often has something to do with the data-type
That's when is is very handy to use the type() function.
just do a
print(type(x))
it will show you the data type of the variable x
