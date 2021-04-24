# Tkinter Windows

## Colors
``` python
  # multiple ways to set background color
  my_window.configure(background='red')
  my_window.configure(bg='red')
  my_window.configure(bg='#ff0000')
```
##Fixed Size Window
```python
  my_window.resizable(width=False, height=False) # window can be minimized, but not maximized.
  my_window.resizable(width=True, height=False)  # only width can be changed. Maximize button will maximize width and not change the height.
  my_window.resizable(width=False, height=True)  # works same for only height resizable.
```
## Location
``` python
  # Uses geometry method
  # coordinates start at 0,0 in top left corner and increase across and down the screen
  # positions are the top left corner of the window.
  my_window.geometry("200x100+0+0")    # String is width, height, x position, y position

  # if you calculate integer variables for width, height, x, y you need to format them to a string.
  # the %d gets replaced with a value and the x and pluses are treated as strings and not changed.
 my_window.geometry("%dx%d+%d+%d" % (width_of_window, height_of_window, x_coordinate, y_coordinate))
```

# Size
``` python
  # Window size attribute can also be set by the configure method.
  my_window.configure(width=400, height=200, background="#94d42b")
  # Or use the geometry method
  my_window.geometry("200x100") # Note this is a string that's passed to the geometry method.
```
## Title
``` python
  my_window.title("Demo1")
```
##Window Information
``` python
  height = winfo_screenheight() # gets the height of the window
  width = winfo_screenwidth() # gets the width of the window.
```
