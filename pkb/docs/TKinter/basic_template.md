
### Tkinter Basic Template

**Basic Template from Codemy.com YouTube**

``` python
# Import all of tkinter
from tkinter import *

# Create root window - Main window of your applicaton usually called root, but
# doesn't have to be. Has to be first in program.
root = Tk()

# Create a label widget
myLabel = Label(root, text="Hello World!")
# Now pack it into the window.
myLabel.pack()


# Create event loop
root.mainloop()

```

**Different way of importing tkinter**

``` python
    # import tkinter module
    import tkinter as tk

    # Create a tkinter instance root is customary but can name it anything.
    root = tk.Tk()

    # Put a caption or title on our window
    root.title("Hello World!")

    # Set the size of the window
    root.geometry("400x400")

    # And the main event loop
    root.mainloop()
```