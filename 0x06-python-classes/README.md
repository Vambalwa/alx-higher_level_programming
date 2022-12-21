0x06. Python - Classes and Objects
QUIZ
Question #0
In this following code, what is User?

class User:
    id = 89
    name = "no name"
    __password = None

    def __init__(self, new_name=None):
        self.is_new = True
        if new_name is not None:
            self.name = new_name

=A class

Question #1
What do these lines print?

>>> class User:
>>>     id = 89
>>>     name = "no name"
>>>     __password = None
>>>
>>>     def __init__(self, new_name=None):
>>>         self.is_new = True
>>>         if new_name is not None:
>>>             self.name = new_name
>>>
>>> u = User()
>>> u.is_new
=True

Question #2
In this following code, what is id?

class User:
    id = 89
    name = "no name"
    __password = None

    def __init__(self, new_name=None):
        self.is_new = True
        if new_name is not None:
            self.name = new_name
=A public class attribute

Question #3
In this following code, what is is_new?

class User:
    id = 89
    name = "no name"
    __password = None

    def __init__(self, new_name=None):
        self.is_new = True
        if new_name is not None:
            self.name = new_name
=A public instance attribute

Question #4
What do these lines print?

>>> class User:
>>>     id = 89
>>>     name = "no name"
>>>     __password = None
>>>
>>>     def __init__(self, new_name=None):
>>>         self.is_new = True
>>>         if new_name is not None:
>>>             self.name = new_name
>>>
>>> u = User()
>>> u.id
=89

Question #5
What do these lines print?

>>> class User:
>>>     id = 89
>>>     name = "no name"
>>>     __password = None
>>>
>>>     def __init__(self, new_name=None):
>>>         self.is_new = True
>>>         if new_name is not None:
>>>             self.name = new_name
>>>
>>> u = User("John")
>>> u.name
=John

Question #6
In this following code, what is __password?

class User:
    id = 89
    name = "no name"
    __password = None

    def __init__(self, new_name=None):
        self.is_new = True
        if new_name is not None:
            self.name = new_name

=A private class attribute

Question #7
What do these lines print?

>>> class User:
>>>     id = 89
>>>     name = "no name"
>>>     __password = None
>>>
>>>     def __init__(self, new_name=None):
>>>         self.is_new = True
>>>         if new_name is not None:
>>>             self.name = new_name
>>>
>>> u = User()
>>> u.name

=no name

