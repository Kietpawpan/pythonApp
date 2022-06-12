# pythonApp
This is my first Window app coded in Python.
The idea is NOT original but slightly modified from the work of Zinglecode, who shows the same app for iOS in YouTube.
I standardized the program for self-training.

__Goal:__ To show the multiplication table for any number except zero.

__Input:__ a number (integer) the user typing in an input box in order to check the multiplication table of that number.

__Output:__ A multiplication table associated with the number keyed by the user.

__Steps:__

# Import the tkinter module for creating a desktop app, and refer to it as tk.
import tkinter
from tkinter import *

# Create a new function called "Show Output", which gets integer number transformed from the text number input
def show_output():
    number = int(number_input.get())

# Check before showing the output. If number equals zero, then show the text "Zero is meaningless" and end the output function.
    if number == 0:
        output_label.configure(text='Zero is meaningless')
        return

# Create an output variable
    output = ''

# Create a loop to perform multiplication from 1 to 12
    for i in range(1,13):
        output += str(number) + ' x ' + str(i)
        output += ' = ' + str(number * i) + '\n'
    output_label.configure(text=output)

# Create a new window for my application
window = Tk()

# Set the size of the app window as 400 x 400 px
window.geometry("400x400")

# Set the name of my app as Lotto 2022.
window.title("Lotto 2022")

# Set the text on what this app does and show it in the window with space between lines at 20 px.
title_label = tkinter.Label(master=window, text='สูตรคูณแม่ n')
title_label.pack(pady=20)

# Add the input box and show it in the window. The box width 15 px.
number_input = tkinter.Entry(master=window, width=15)
number_input.pack()

# Add the button, namely ได้แก่ and show it, but add the command of show_output too.
# Set the button size as
go_button = tkinter.Button(
    master=window, text='ได้แก่',
    command=show_output, width=15, height=2
)
go_button.pack()

# Show the output with 20 px space vertically
output_label = tkinter.Label(master=window)
output_label.pack(pady=20)

# Show the app window
window.mainloop()
