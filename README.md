# python-dialog-messagebox

Python code that uses the Gtk class **MessageDialog**.

The program **dialog_demo.py** opens a *Gtk.MessageDialog()* window that contains a *Gtk.Entry()* widget. The user 
may then type in entries like a user name, a password, or pin code, etc.

After entering the data, the Enter key triggers the data to be returned to the function
that made the call, and the MessageDialog box is closed.

Copy the function *def input_dialog()* and call it with a function like:

`response = self.input_dialog("Enter Name", "Enter your name")`

The program **dialog_demo_timeout.py** opens a *Gtk.MessageDialog* window and displays a message for a few
seconds. It then closes the MessageDialog box. It is effectively a pop-up window that can be used to warn 
the User of, say, "Exceeding limit of login attempts".

The program **dialog_demo_timeout_css.py** introduces Cascading Style Sheets (CSS) to modify fonts and
colours, etc.


Tested with Gtk version 3.24.18

Ian 2020-06-29

