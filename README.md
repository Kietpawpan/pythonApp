# 1. MultiplyN
MultiplyN is my first Window app. The idea is NOT original. I modified the work of Zinglecode, who developes the same app for iOS. I just made it works for Windows and more international.

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
11. Show the button (marked as Run) with the command of show_output.
12. Resize the button width to 15 px.
13. Show the output, with 20-px space between lines.
14. Show the app window on the desktop of the computer.

# 2. ID Generator
This app was developed for my office.

__Goal:__ To generate a User ID for accessing the e-tracking service

__Input:__ The first name and the surname (String in Thai) of the user

__Output:__ The User ID text, which combines the first English chracter of name, surname, and a time-based serial number 

__Steps:__

1. Import the tkinter module for creating a desktop app.
2. Import datetime module for getting the present time
3. Set the time format as yyyymmddhhmm
4. Get the value yymmddhhmm as the user ID suffix
5. Create a new function called "Show Output", which gets integer number transformed from the text number input
6. Get the values from the two input boxes (first name and surname)
7. Create a new dictionary for translate the username and surname into English. Avoid using 'I', which seems like 1. 
8. Use various English characters for Thai vowels
9. Create separate dictionary tables for username and surname translation
10. Translate the username and put the value in a new variable called transName
11. Translate the surname and put the value in a new variable called transSurname
12. Set the value for the output, which combines the first characters of the translated username and surname plus the Integer ID
13. Show the output as text
14. Create a new window for my application
15. Set the size of the app window as 400 x 400 px
16. Set the name of my app as jTech ID Generator.
17. Set the text on what this app does and show it in the window with space between lines at 20 px.
18. Create two text messages to describe the two input boxes
19. Set the locations of the text
20. Set the type of input data as String (plain text)
21. Create an input box for the first name of the user, and set its location
22. Create an input box for the surname, and set its location
23. Add a button, named 'Get ID', and add this command: 'show_output'
24. Set the button size as
25. Pack the button to the screen
26. Show the output on the screen with 20 px space vertically
27. Show the app window
