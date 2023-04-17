1. See object as a class
2. There are functions inside this class called methods
3. Each function must have "self" parameter as a default/parameter that represent instance

Example :
class Kitty:
  """Represent a cat that can sa their name"""  % This is docstrings / part of documentation which able to describe classes, functions and methods
  years = 0
  name = ""
  def speak(self):
    """Outputs a message including the name of the cat"""
    print("Meow! I'm {}! Meow!".format(self.name))
  def cat_years(self)
    """Converts the current age to equivalent cat years"""
    return self.years * 18

>> help(Kitty)

Question
1. How to call functions indside 
  class className:
    def __init__(self, top, bottom, current):
      self.top = 0
      self.bottom = 0
      self.current = 0
    def up(self):
      self.current = current + 1
      if self.current > top:
        self.current = current
    def down(self):
    def go_to(self, floor)
       self.current = floor
       
  >> object = className(parameter01, parameter02, ...)
  >> object.up()
  >> object.down()
  >> object.go_to(-1)       % since it has 1 more parameter other than "self" parameter
