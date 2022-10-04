if it's not tested it doesn't work.
Create class base, private class attribute __nb_object = 0,
	class constructor def __init__(self, id=None).
Create class Rectangle, Private instance attributes,
	each with its own public getter and setter.
	class constructor def __init__(self, with,height, x=0,y=0, id=None).
Update class rectangle by adding validation of all setter methods and instantiation.
Update class Rectangle by adding thr public method def area(self) that returns
	area valueof the Rectangle instance.
Update class Rctangle by adding the public method def display(self) that prints
	in stdout the Rectangle instance with the character #.
Update the Rectangle by overriding the __str__ method.
Update the class Rectangle by improving the public method def display(self):
	to print in stdout the Rectangle instance with the charcter #.
Update the calss Rectangle by adding the public method def update(self, *args):
	that assigns an argument to each attribute.
Update the class Rectangle by updating the public method def update(self, *args):
	by changing the prototype to update(self, *args, **kwargs) that assigns
	a key/value argument to attributes.
Write a class Square that inherits from Rectangle.
update the calss square by adding the public gette and setter size.
Update the class Square by adding the public ethod def update(self, *args, **kwargs)
	that assigns attributes.
Update the class Rectangle by adding the public method def to_dictionary(self):
	that returns the dictionary representation of a Rectangle.
Update the class Square by adding the public method def to_dectionary(self):
	that returns the deictionary representation of a square.
Update the class Base by adding the static method def to_json_string(list_dictionaries):
	that returns the JSON string representation of list_dictionaries. 
