#  Codemy Tk Entry Fields YT Vid4
##  Intro to tkinter entry fields

``` Python
# First import tkinter
from tkinter import *

# Now create the main window. Typically called root but can be named most anything.
root = Tk()

# input boxes are called entry widgets in tkinter
# Can set colors, width etc just like with other widgets.
# Borderwidth usable on entry widget.

e = Entry(root)
e.pack()
# .insert() lets you put a default value in the entry box
# 0 means the zeroth box, not sure when you would use anything other than zero
e.insert(0, "Enter Your Name:")

# .get() function gets text from the box.

def myClick():
    myLabel = Label(root, text="Hello " + e.get())
    myLabel.pack()

myButton = Button(root, text="Enter Your Name!", command=myClick)

myButton.pack()

# Create the event loop that waits for user to do things on the screen

root.mainloop()
```
