## python chai.py 

 first an software/interpreter is used named python and then the file name is given which is a program/script. 


### Code/script => byte code (mostly hidden){mostly visible when we import a fn} => Python VM (this also gets installed with the python and its is the interface that actually runs your code.)

compile to byte code (low lvl and platform independent can run anywhere there is a VM) // this is not a compiler language the use of word "Compile" is just a tech jargen.

byte code runs faster as all check are already done (mostly are done => like syntax check and parsing)

.pyc =. compiled python (frozen binary)

__pycache__ (these are for internal use of python)

DFA difference finding algorithms to see what changes are there and only push those, (internally)

hello_chai.cpython-312.pyc (cpython-312 is the python version)
-> works only for the imported files
-> not for top level files

as when not imported files dont need any kind of optimisation we can directly push them. 

It tells that the python got made into bits on this version of the python

### Python Virtual Machine PVM

=> code loop to iterate byte code
=> Run time engine ( same engine is used in jupyter and anaconda)
=> Also known as python interpreter.

#### Byte code is not machine code
=> python specified interpreter
we are currently using cpython which is standard implementation so cpython (Clang) = python
=> cpython, jython, IronPython, Stackless, Pypy

this is the only all the programs run in python 

##### we just need to look into memory (mutable and immutable) seperatly other than that we have covered all that goes behind in python for the most part

blog on hashcode
