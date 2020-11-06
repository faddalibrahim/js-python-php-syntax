```python

dir("") #display all the attributes and methods in a class
help("") #documention of the class


class Apple:
    color = "pink"
    flavor = ""


    def speak(self):
        """prints the color of the object"""
        print(self.color)

apple = Apple()
apple.color = "red"
apple.flavor = "sweet"



class Banana:

    def __init__(self,color,flavor):
        self.color = color
        self.flavor = flavor

    def speak(self):
        print(self.color)

    def __str__(self):
        return "I am a banan class"

banana = Apple("green","bitter")

with the __str__ method, printing any instance of the banana class will print what was set in the block fo the method



class Ban(Banana):

granny = Ban(color,flavor)

```