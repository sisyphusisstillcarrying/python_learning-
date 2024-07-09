this is a straight forward language and not that much internal detailing with low inconsistencies (mutable and immutable).

everything in python is called object. (string object, integer object)

[mutable and immutable](https://media.licdn.com/dms/image/D4E12AQEvWID2rFeudA/article-cover_image-shrink_600_2000/0/1679695596993?e=2147483647&v=beta&t=cLj7kNXvqyVcilTBwB-fapw-vcgxfQeOM9Uda7BqqZw)

''' python
>>> x = 10
>>> y = x # step 1
>>> x 
10
>>> y
10
>>> x = 15 # step 2
>>> x
15
>>> y
10
'''

#### python has a garbage collector
immutable in python means that the referance (assigned position or address in memory) that has been made for that object (str obj, int obj etc) in the memory will not change but rather when we put some other value like 10 here. it gets stored in the new reference and the attribute points to that.

we can add another reference in the attribute but we cannot change in individual object "14"

[Step 1](images/before.png)
[Step 2](images/after.png)

#### mutable data can get changed at that reference in memory  

we cannot change any string internally 
for eg we cannot make chaiaurcode to chaiAURcode. to do this we will need to make a new string and point to it.
