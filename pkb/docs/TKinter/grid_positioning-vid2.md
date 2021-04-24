# Codemy Tk Grid YT Vid2
## Grid System Introduction


``` Python
#  Codemy Tkinter YouTube Video 2
#  Intro to the Grid System - position like on a spreadsheet

# First import tkinter
from tkinter import *

# Now create the main window. Typically called root but can be named most anything.
root = Tk()

# Create a couple of label widgets

myLabel1 = Label(root, text="Hello World!")
myLabel2 = Label(root, text="My Name is Terry Dutcher")

# Put the label widgets onto the screen using the Grid System. 
# Grid system rows and columns both start with zero.
# These are relative to each other - so if change myLabel2 to column 5 makes no difference
# Since columns 1,2,3,4 would be empty.

myLabel1.grid(row=0, column=0)
myLabel2.grid(row=1, column=1)

# Create the event loop that waits for user to do things on the screen

root.mainloop()
```
