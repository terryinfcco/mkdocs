# Menus

###Codemy Video 15 Menus Part 1

``` python
# Create a menu with a single sub menu
my_menu = Menu(root)
root.config(menu=my_menu)

# Create the sub menu
file_menu = Menu(my_menu)

# add an item to the submenu
my_meny.add_cascade(label-"File", menu=file_menu)
file_menu.add_command(label="New", command=fake_function)
file_menu.add_command(label="Exit", command=root.quit)

# To add a seperator to a menu
file_menu.add_seperator()
```

### Codemy Video 16 Menus Part 2

``` python
# Create a menu with a single sub menu
my_menu = Menu(root)
root.config(menu=my_menu)

# Create the sub menu
file_menu = Menu(my_menu)

# add an item to the submenu
my_meny.add_cascade(label-"File", menu=file_menu)
file_menu.add_command(label="New", command=fake_function)
file_menu.add_command(label="Exit", command=root.quit)

# To add a seperator to a menu
file_menu.add_separator()

```

This code adds another sub menu - an Edit menu

``` python
# Create the edit menu
edit_menu = Menu(my_menu)

# Create the main heading
my_menu.add_cascade(label="Edit", menu=edit_menu)

# Add these items to the menu
edit_menu.add_command(label="Cut", command="cut_function")
edit_menu.add_command(label="Copy", command="copy_function")
edit_menu.add_command(label="Paste", command="paste_function")
```
