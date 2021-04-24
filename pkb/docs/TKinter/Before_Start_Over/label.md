# Codemy Video 6 Labels

Labels put text on the tkinter screen.

Pretty much everything in tkinter is a widget. Putting a widget on the screen is a 2 step process. You create the widget and then you put it on the screen with pack, grid, etc. Pack is the easiest, but doesn't give you much control. He uses the grid system mostly.

``` python
# first import the tkinter module
from tkinter import *

# Create instance of tkinter. Doesn't have to be root, any valid python
# variable name. But it's the root window.
root = Tk()

# Window title
root.title("Hello World!")

# Set the size of our window
root.geometry("400x400")

# Create a basic label
my_label = Label(root, text="Hello World!")
my_label.pack()
my_label2 = Label(root, text="Second Label!")
my_label2.pack()

# This goes at the bottom of the program and creates the event loop.
root.mainloop()

```

## Tkinter Labels

    # Create the label widget
    myLabel = tk.Label(root, text="Hello World!")

    # Pack it on the screen
    myLabel.pack()
