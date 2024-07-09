to access it type python3 in terminal and python shell is opened. 

to access it on windows type python.

cntrl + Z/D to exit the shell. or suspended python


click the folder and select open in intergrated terminal and now the terminal is open in the folder. 

=> learn linux basic cmd - cd ls etc

this can be used for small code testing to see how it will react in python

#### we import a lot of module libraries etc etc 
most of the code is already written in python that is the reason why it is popular.

here we can import directly as core module so python knows where to get it 
              like import os (file and module) now we can use all the functionality of this module

... means the cmd is still going on 

either python can import knowing where it is or otherwise first it will look inside the current directory and then other directly foe the import you have asked it to search for


we can also inport and to the function in python shell

import hello_chai
>>> hello_chai.chai("mint tea")
mint tea (o/p)

#### if we add attributes to the py file after import those are note accessable. we need to import again.
 we can re import or access it by reopening terminal and importing but we will use reload

 >>> from importlib import reload
 >>> reload(hello_chai)

errors (till now)
1. Indentation
2. namespace <stdin>
3. attributes/variable: Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
  NameError: name 'chai' is not defined

