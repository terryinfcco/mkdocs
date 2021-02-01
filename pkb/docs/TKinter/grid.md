## Tkinter Grid System

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