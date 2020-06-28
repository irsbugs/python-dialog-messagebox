# python-dialog-messagebox

Using the Gtk class **MessageDialog** a Gtk.Entry widget is all that is provided to capture
entries like user name and password.

After entering the data, the Enter key triggers the data to be returned to the function
that made the call, and the MessageDialog box is closed.

Copy the function *def input_dialog()* and call it with a function like:

`response = self.input_dialog("Enter Name", "Enter your name")`

Tested with Gtk version 3.24.18

Ian 2020-06-28

