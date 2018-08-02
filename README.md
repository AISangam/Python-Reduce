# Python-Reduce
## Pytho Reduce purpose in Python
This module is defined under the module functools and is used to apply a particular function passed as a argument to all the elements of the list which is considered as the other argument of the function reduce.
### Let us see the following program to illustrate the use case of it
```
Write a Program to multiply every element of the list by its previous element and resultant element of the product is multiplied to the next element of the list
import functools
list1 = [1, 2, 3]
functools.reduce(lambda a,b:a*b,list1)
```
This will return the result as 6

This makes the code look more decent and effective while saves many bunches of lines.

### How to run this file  
Since this file is run using jupyter notebook so you needd to install jupyter notebook and run the following command
```
jupyter notebook
```


