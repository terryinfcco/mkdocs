# Codemy Video 7 Label Options

**Applicable to almost all widgets**

``` python
# Change the foreground and background colors. Can also use hex codes.
my_label = Label(root, text="Hello World!", fg="white", bg="black")
my_label.pack()

# Change the font and relief (flat [default], sunken, raised, groove and ridge)
my_label2 = Label(root, text="Second Label!", font=("Arial", 32), relief="sunken")
my_label2.pack()

# Change the state - more often used for buttons. Normal is default, disabled grays out the text.
my_label3 = Label(root, text="Third Label!", state="disabled")
my_label3.pack()

# Change height and width, makes more sense in grid than pack.
my_label4 = Label(root, text="Fourth Label!", height=200, width=200)
# Can change padding in pack statement
my_label4.pack(pady=50, padx=20)

# This goes at the bottom of the program and creates the event loop.
root.mainloop()

```
