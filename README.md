# Python-Basics-Project
It contains the project homework of the Python Basics education in the Project Coded-Patika.

## PROJECT

1- Write a function that flattens a list. Its elements can consist of multi-layered lists (such as [[3],2]) or non-scalar data. For instance:

input: [[1,'a',['cat'],2],[[[3]],'dog'],4,5]

output: [1,'a','cat',2,3,'dog',4,5]

2- Write a function that reverses the elements inside the given list. If the elements inside the list also contain the list, reverse their elements as well. For instance:

input: [[1, 2], [3, 4], [5, 6, 7]]

output: [[[7, 6, 5], [4, 3], [2, 1]]

### Solution - 1

#numpy.ndarray.flatten() function

import numpy as np

arr = np.array([[5,6], [7,8]])

esin = arr.flatten()

print(esin)

### Solution - 2

# to create a list of numbers

numbers = [2,3,5,7]

#reverse the order of list elements

numbers.reverse()

print('Reversed List:', numbers)

