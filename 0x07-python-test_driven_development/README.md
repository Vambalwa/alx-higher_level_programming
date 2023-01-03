0x07. Python - Test-driven development
The Quiz Bit
Question #0
Is this a standardized way to comment a function in Python?

/* Addition function */
def add(a, b):
    return a + b
=No

Question #1
Is this module correctly commented?

#!/usr/bin/python3
"""
    My calculation module
"""
import sys
...

=Yes

Question #2
Is this a standardized way to comment a function in Python?

"""" Addition function """
def add(a, b):
    return a + b
=No

Question #3
Is this a standardized way to comment a function in Python?

def add(a, b):
    """ Addition function """
    return a + b
=Yes

Question #4
Is this module correctly commented?

#!/usr/bin/python3
import sys

"""
    My calculation module
"""
...
=No

Tips:
Docstring must be before import statements

Question #5
Based on this code, what should all the test cases be? (select multiple)

def uniq(list):
    """ Returns unique values of a list """
    u_list = []
    for item in list:
        if item not in u_list:
            u_list.append(item)
    return u_list
=list with 2 different element (same type)
list with twice the same element (same type)
list with more than 2 times the same element (same type)
not a list argument (ex: passing a dictionary to the method)
empty list
list with multiple types (integer, string, etc…)
list with one element (any type)

Question #6
Is this a standardized way to comment a function in Python?

##########
# Addition function
##########
def add(a, b):
    return a + b
=No
