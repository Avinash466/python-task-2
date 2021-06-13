# python-task-2
Python 3.9.5 (tags/v3.9.5:0a7dcbd, May  3 2021, 17:27:52) [MSC v.1928 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license()" for more information. 

HOW TO A PRINT A VALUE?
>>> print("30 days 30 hours challenge")
30 days 30 hours challenge

ASSIGNING STRING TO VARIABLE
>>> Hours="thirty"
>>> print(Hours)
thirty

INDEX USING STRING
>>> Days="Thirty days"
>>> print(Days[0])
T

HOW TO PRINT THE PARTICULAR CHARACTER FROM CERTAIN TEXT?
>>> Challenge="I will win"
>>> print(Challenge[7:10])
win

PRINT THE LENGTH OF CHARACTER:

>>> Challenge="I will win"
>>> print(len(Challenge))
10

CONVERT STRING INTO LOWER CHARACTER 
>>> Challenge="I will win"
>>> print(Challenge.lower())
i will win

STRING CONCATENATION-JOINING TWO STRINGS

>>> a="30 Days"
>>> b="30 hours"
>>> c=a+b
>>> print(c)
30 Days30 hours

ADDING SPACE DURING CONCATENATION

>>> a="30 Days"
>>> b="30 hours"
>>> c=a+""+b
>>> print(c)
30 Days30 hours

CASEFOLD() - USAGE

>>> text="Thirty days and Thirty hours"
>>> x=text.casefold()
>>> print(x)
thirty days and thirty hours
  
>>> text="DON'T TROUBLE TROUBLE UNTIL TROUBLE TROUBLES YOU."
>>> x=text.capitalize()
>>> print(x)
Don't trouble trouble until trouble troubles you.
  
>>> text="DON'T TROUBLE TROUBLE UNTIL TROUBLE TROUBLES YOU."
>>> x=text.find()
>>> print(x)
Don't trouble trouble until trouble troubles you.
  
>>> text="DON'T TROUBLE TROUBLE UNTIL TROUBLE TROUBLES YOU."
>>> x=text.isalpha()
>>> print(x)
False
  
>>> text="DON'T TROUBLE TROUBLE UNTIL TROUBLE TROUBLES YOU."
>>> x=text.isalnum()
>>> print(x)
False
