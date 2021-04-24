#Images

###Codemy Video 13 Images

Don't use what's built into Python. It's very out of date.

``` bash
# Make sure you're in the correct directory and your venv is active.
pip[3] install Pillow
```

``` python
# Imports needed for images
from PIL import ImageTk, Image
# You can add an image to almost any widget
# png and jpg both work
my_image = ImageTk.PhotoImage(Image.open("images/testimage.png")
image_label = Label(image=by_image)
image_label.pack()
```
