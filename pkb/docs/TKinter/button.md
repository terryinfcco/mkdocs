## Buttons in Tkinter

Normal format root is the container where you want the button, text is what is displayed
on the button, command points to the function that needs to be executed when the button is
clicked.

    myButton = tk.Button(root, text="Click Me!", command = myClick)
    
    

Note that you don't include parentheses on the function call. 