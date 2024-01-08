In this project, We look at Python class inheritance. We see the differences between super- and sub-classes while practicing inheritance, definitialising classes with multiple base classes, and overiding inherited methods and attributes.

0-lookup.py: Python function that returns a list of available attributes and methods of an objects.

1-my_list.py: Python class MyList that inherits from list. Includes:
Public instance method def print_sorted(self): that prints the list in ascending sorted order (assumes all list elements are ints).

2-is_same_class.py: Python function that returns True if an object is exactly an instance of a specified class; otherwise False.

3-is_kind_of_class.py: Python function that returns True if an object is an instance or inherited instance of a specified class; otherwise False.

4-inherits_from.py: Python function that returns True if an object is an inherited instance (either directly or indirectly) from a specified class; otherwise False.

5-base_geometry.py: An empty Python class BaseGeometry.

6-base_geometry.py: Python class BaseGeometry. Builds on 5-base_geometry.py with:
Public instance method def area(self): that raises an Exception with the message area() is not implemented.

7-base_geometry.py: Python class BaseGeometry. Builds on 6-base_geometry.py with:
Public instance method def integer_validator(self, name, value): that validates the parameter value.
Assumes the parameter name is always a string.
The parameter value must be an int, otherwise, a TypeError exception is raised with the message <name> must be an integer.
The parameter value must be greater than 0, otherwise, a ValueError exception is raised with the message <value> must be greater than 0.


