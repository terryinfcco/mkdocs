# Forget and Destroy

### Codemy Video 14 Pack/Grid Forget and Destroy

Two ways to have a widget not appear on the screen. One if you want it back, another if you're sure you're done with it.

``` python
# Function to Hide the widget
def hide():
   global my_label2
   my_label2.pack_forget()
def show():
   global my_label2   
# reshow a label that's already been created, but has been hidden.
   my_label2.pack()

# or completely get rid of it. Would have to be recreated to reappear
my_label2.destroy()

```
