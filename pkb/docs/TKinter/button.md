## Buttons in Tkinter

**Codemy.com Youtube Video 3**

``` python
# Import all of tkinter
from tkinter import *

# Create root window - Main window of your applicaton usually called root, but
# doesn't have to be. Has to be first in program.
root = Tk()

# Create a button. Need a function that the button calls first.

def myClick():
    myLabel = Label(root, text="You clicked the Button!!")
    myLabel.pack()

# Use command= to call a function. Notice that there are no parentheses
# for parameters.
# myButton = Button(root, text="Click Me!", command=myClick)

# Change the foreground color with fg and background color with bg
# Can also use hex codes bg="#ffffff" or fg="#000000"
myButton = Button(root, text="Click Me!", command=myClick, fg="blue", bg="orange")

# Add padding which is inside the button borders
# myButton = Button(root, text="Click Me!", padx=50, pady=50)

# if you want the button grayed out so it can't be clicked:
# myButton = Button(root, text="Click Me!", state=DISABLED)

myButton.pack()


# Create event loop
root.mainloop()

```

**Older Notes**
Normal format root is the container where you want the button, text is what is displayed
on the button, command points to the function that needs to be executed when the button is
clicked.

    myButton = tk.Button(root, text="Click Me!", command = myClick)
    
    

Note that you don't include parentheses on the function call. 