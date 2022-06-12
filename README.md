# pythonApp
This is my first Window app coded in Python.
The idea is NOT original but slightly modified from the work of Zinglecode, who shows the same app for iOS in YouTube.
I standardized the program for self-training.

__Goal:__ To show the multiplication table for any number except zero.

__Input:__ a number (integer) the user typing in an input box in order to check the multiplication table of that number.

__Output:__ A multiplication table associated with the number keyed by the user.

__Steps:__

1. Import the tkinter module for creating a desktop app
2. Create a new function called "Show Output", which gets integer number transformed from the text number input.
3. Check before showing the output. If the number is zero, then show the text "Zero is meaningless" and end the output function.
4. Create the output variable.
5. Create a loop to show the multiplication table for any number multipled by 1 to 12.
6. Create a new window for my application, which is the user interface of this app.
7. Set the size of the window as 400 x 400 px
8. Show the name of my app as MuliplyN, on the title bar of the window.
9. Show the text that describes what this app can do, in the window, with 20-px space between lines.
10. Add the input box in the window. The box width is 15 px.
11. Show the button (marked as ได้แก่) with the command of show_output.
12. Resize the button width to 15 px.
13. Show the output, with 20-px space between lines.
14. Show the app window on the desktop of the computer.
