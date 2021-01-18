## Tkinter Grid System

Typical grid - rows and columns. Both are numbered from zero. 

    # Create two label widgets
    myLabel1 = tk.Label(root, text="Line 1")
    myLabel2 = tk.Label(root, text="Line 2")
    
    myLabel1.grid(row=0, column=0)
    myLabel2.grid(row=1, column=0)

The rows and columns are relative to each other if you put myLabel2 into column 1 or column 5 it's in the column next to column 0. Tkinter just ignores empty columns or rows.