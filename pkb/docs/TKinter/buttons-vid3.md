# Codemy Tk Buttons YT Vid3
## Tkinter Buttons Introduction

``` Python
#  Codemy Tkinter YouTube Video 3
#  Intro to tkinter buttons

# First import tkinter
from tkinter import *

# Now create the main window. Typically called root but can be named most anything.
root = Tk()

def myClick():
    myLabel = Label(root, text="Look! I clicked a Button!")
    myLabel.pack()

# Like everything in tkinter, a button is a widget.
# Can add a state to the button - , state=DISABLED would grey out the button so it can't be clicked
# padx makes button wider, pady makes button taller
# fg changes foreground color, bg changes background color. Can use name of color or hex color code.
# command causes clicking the button to execute a function. Note that you don't use parentheses
# to pass parameters to the function.

myButton = Button(root, text="Click Me!", padx=50, pady=50, fg="blue", bg="red", command=myClick)

myButton.pack()

# Create the event loop that waits for user to do things on the screen

root.mainloop()
```
