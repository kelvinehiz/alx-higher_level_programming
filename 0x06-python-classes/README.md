In this project, we are introduced to object-oriented programming with the usage of classes and objects in Python. We look at  attributes, methods and their properties.

0-square.py: Python class Square that defines a square.

1-square.py: Python class Square that defines a square. Builds on 0-square.py with:
-Private instance attribute size.
-Instantiation with size.

2-square.py: Python class Square that defines a square. Builds on 1-square.py with:
-Instantiation with optional size: def __init__(self, size=0):

3-square.py: Python class Square that defines a square. Builds on 2-square.py with:
-Public instance attribute def area(self): that returns the current square area.

4-square.py: Python class Square that defines a square. Builds on 3-square.py with:
-Property def size(self): to retrieve the private instance attribute self.
-Property setter def size(self, value): to set self.

5-square.py: Python class Square that defines a square. Builds on 4-square.py with:
-Public instance method def my_print(self): that prints the square with the character # to standard output (if size == 0 -> prints an empty line).

6-square.py: Python class Square that defines a square. Builds on 5-square.py with:
Private instance attribute position.
Property def position(self): to retreive position.
-Property setter def position(self, value): to set position.
-Instantiation with optional size and position: def __init__(self, size=0, position=(0, 0)):

100-singly_linked_list.py: Python classes Node and SinglyLinkedList that define a node of a singly-linked list and a singly-linked list. 

101-square.py: Python class Square that defines a square. Builds on 6-square.py with:
-Method __str__ to set printing of a Square instance equivalent to my_print().

102-square.py: Python class Square that defines a square. Builds on 101-square.py with:
-Methods __eq__, __ne__, __lt__, __le__, __gt__, and __ge__, to enable usage of Square instances with logical operators ==, !=, <, <=, >, and >=, respectively, based on the square area.

103-magic_class.py: Python function matching exactly a bytecode provided by ALX.
