#  Codemy Tk Template YT Vid1
## Basic Template for Tkinter

``` python
#  Codemy Tkinter YouTube Video 1

# First import tkinter
from tkinter import *

# Now create the main window. Typically called root but can be named most anything.
root = Tk()

# Create a couple of label widgets

myLabel = Label(root, text="Hello World!")
myLabel2 = Label(root, text="Line Two")

# Pack the label widgets onto the screen

myLabel.pack()
myLabel2.pack()

# Create the event loop that waits for user to do things on the screen

root.mainloop()
```
