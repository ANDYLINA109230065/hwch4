Python 3.8.3 (default, Jul  2 2020, 17:30:36) [MSC v.1916 64 bit (AMD64)] :: Ana
conda, Inc. on win32
Type "help", "copyright", "credits" or "license" for more information.
>>> a=100
>>> b=200
>>> c,d=a,b
>>> print(c,d)
100 200
>>> print(c)
100
>>> print(d)
200
>>> print()

>>> a=100
>>> b=200
>>> c,d=a,b
>>> print(c,d)
100 200
>>> print(c,end='')
100>>> print(d,end='***')
200***>>> print('Over')
Over
>>> a=100
>>> b=200
>>> c,d=a,b
>>> print(c,d)
100 200
>>> print(c,end='$'
... print('abd')
  File "<stdin>", line 2
    print('abd')
    ^
SyntaxError: invalid syntax
>>> print(c,end='$')
100$>>> print('and')
and
>>> print(d,end='***')
200***>>> print('Over')
Over
>>> x=100
>>> y=3
>>> print(x*y)
300
>>> print(x/y)
33.333333333333336
>>> print(x//y)
33
>>> print(x%y)
1
>>> print(x**y)
1000000
>>> print(x**0.5)
10.0
>>> str1='Hello,'
>>> str2="Python"
>>> str3=str1+str2
>>> print(str3)
Hello,Python
>>> a=100
>>> b=200
>>> c=a+b
>>> print(c)
300
>>> str1='Hello,'=\
... 'Python,Let\'s learning'
  File "<stdin>", line 1
SyntaxError: cannot assign to literal
>>> str1='Hello,'=\
  File "<stdin>", line 1
    str1='Hello,'=\
                   ^
SyntaxError: unexpected character after line continuation character
>>> str1='Hello,'+\
... 'Python,Let\'s lrarning'
>>> str2="Python now"
>>> str3=str1+str2
>>> print(str3)
Hello,Python,Let's lrarningPython now

>>> a=100
>>> b=3
>>> a//=b
>>> print(a)
33
>>> a=100
>>> a%=b
>>> print(a)
1
>>> a=100
>>> a/=b
>>> print(a)
33.333333333333336
>>> a=100
>>> b=200
>>> print(a,b)
100 200
>>> b,a=a,b
>>> print(a,b)
200 100
>>> a=100
>>> b=200
>>> print(a,b)
100 200
>>> temp=a
>>> a=b
>>> b=temp
>>> print(a,b)
200 100
>>> a=eval(input('Enter an integer'))
Enter an integerb=a+100
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
  File "<string>", line 1
    b=a+100
     ^
SyntaxError: invalid syntax
>>> b=a+100
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'a' is not defined
>>>
>>> a=eval(input('Enter an integer:'))
Enter an integer:b=a+100
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
  File "<string>", line 1
    b=a+100
     ^
SyntaxError: invalid syntax
>>> a=eval(input('Enter an integer:'))
Enter an integer:
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
  File "<string>", line 0

    ^
SyntaxError: unexpected EOF while parsing
>>> str1=input('Enter a string:')
Enter a string:str2=str1+'i8'
>>> print(str2)
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'str2' is not defined
>>>
