## Tkinter Entry Widget

Allows user to enter data. 

    e = tk.Entry(root, width=50)
    e.delete(0, END) # Clears the box
    e.insert(0, "Enter Your Data")  # Puts default data in the entry box, 0 he didn't explain
    text_from_entry = e.get()