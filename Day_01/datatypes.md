# Object Types / Data Types

- Number : 1234, 3.1415, 3+4j, 0b111, Decimal(), Fraction()
- String : 'spam', "Bob's", b'a\x01c', u'sp\xc4m'
- List : [1, [2, 'three'], 4.5], list(range(10)) 
<!-- this starts from 0 ans we cannot change that. 0,1,2,3 etc we can put list inside a list -->
- Tuple : (1, 'spam', 4, 'U'), tuple('spam'), namedtuple
- Dictionary : {'food': 'spam', 'taste': 'yum'}, dict(hours=10)
<!-- in dictionary/dict we dont have to start from 0 here there is a key and a value -->

- Set : set('abc'), {'a', 'b', 'c'}

- File : open('eggs.txt'), open(r'C:\ham.bin', 'wb')
<!-- file mechansim some text types work directly in python without need of libraries.
we can use the data from files using modules that are prewritten  -->

- Boolean : True, False
- None : None
<!-- empty reference rather than entering 0 eg in temperature app -->

- Funtions, modules, classes

- Advance: Decorators, Generators, Iterators,

- MetaProgramming


### python support high accurecy and high values
```
>>> 12 + 12
24
>>> 12.5*5 // accuracy
62.5
>>> 2 ** 100  // power and high values 
1267650600228229401496703205376


>>> import math
>>> math.pi
3.141592653589793
>>> import random
>>> random.random()
0.7455257268641734
>>> random.choice([1,5,4,8,9])
8
>>> username = "chaiaurcode"
>>> len(username) //length
11
>>> username[0]
'c'
>>> username[0] = "A"
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
TypeError: 'str' object does not support item assignment
>>> username[-2]
'd'
>>> username[1:3] //starts from 1 and end before three
'ha'
>>> dir(username) // show all the posibilites with the username
```

```
>>> mylist = [123,"chai",3.14]
>>> mylist
[123, 'chai', 3.14]
>>> len(mylist)
3
>>> mylist[1]
'chai'
>>> mylist[-1]
3.14
>>> myD = {'one':'lemon','two ':'ginger'}
>>> myD
{'one': 'lemon', 'two ': 'ginger'}
>>> myD['ginger']
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
KeyError: 'ginger'
>>> myD['two ']
'ginger'

```
#### cntrl + / (shortcut for comment in any language in vscode)

<!-- vscode comment -->
list is more used than tuples