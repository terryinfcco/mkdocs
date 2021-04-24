## Tkinter Grid System

### Codemy Video 8 Pack vs. Grid

You can use both pack and grid at the same time but until you're advanced, don't!
Grid is laid out in rows and columns like a spreadsheet.

``` python
# Comments start with a # sign.
# examples of grid commands after creating labels.
my_label.grid(row=0,column=0)
my_label2.grid(row=1, column=0)

# This goes at the bottom of the program and creates the event loop.
root.mainloop()

```
###Codemy Tkinter Video 9 Grid Options

Size of a row or column defaults to the size of the largest widget in that row or column. Other widgets in that row or column default to centered. But you can change that using the sticky option and compass directions.

``` python
# Use E, W, N, S for right, left, top, bottom
my_label2.grid(row=1, column=0, sticky=W)
```

Column span and row span lets one cell span a row or column
``` python
my_label.grid(row=0, column=0, columnspan=2)
```

**Codemy.com Youtube Video 2**

``` python
# Import all of tkinter
from tkinter import *

# Create root window - Main window of your applicaton usually called root, but
# doesn't have to be. Has to be first in program.
root = Tk()

# Create 2 label widgets
myLabel1 = Label(root, text="Hello World!")
myLabel2 = Label(root, text="My Name is Terry")

# First put it into the window in a grid one on top of the other.
myLabel1.grid(row=0, column=0)
# myLabel2.grid(row=1, column=0)

# Now try Label2 in column 1
# myLabel2.grid(row=1, column=1)

# Now put Label2 in column 5 and notice that nothing changes
# Columns are relative to each other and since columns 1-4 don't exist
# Tkinter ignores them.
myLabel2.grid(row=1, column=5)


# Create event loop
root.mainloop()
```
** Older Notes**

Typical grid - rows and columns. Both are numbered from zero.

``` python
    # Create two label widgets
    myLabel1 = tk.Label(root, text="Line 1")
    myLabel2 = tk.Label(root, text="Line 2")

    myLabel1.grid(row=0, column=0)
    myLabel2.grid(row=1, column=0)
```

The rows and columns are relative to each other if you put myLabel2 into column 1 or column 5 it's in the column next to column 0. Tkinter just ignores empty columns or rows.
