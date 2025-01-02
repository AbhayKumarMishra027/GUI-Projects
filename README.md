LOGIN SYSTEM

This is a simple login system GUI built using the customtkinter library, which provides a modern and customizable theme for Tkinter applications. This project uses a dark theme with a blue color scheme and includes basic functionality for user authentication.

Features

Modern Dark Theme: The application uses a custom dark-blue theme to enhance the user interface.
Username and Password Fields: Users can enter their username and password.
Login Button: The login button triggers the login action.
Remember Me Checkbox: The checkbox allows users to opt for remembering their credentials.

Code Explanation

GUI Layout

The window is created using customtkinter.CTk() and set to 500x350 pixels.
The frame holds the main content of the login form.
The label displays the text "Login System" at the top.
CTkEntry widgets are used for the username and password input fields. The password field is masked using the show="*" parameter.
The Login button triggers the login function that simulates user authentication.
The Checkbox widget allows the user to choose whether they want to remember their credentials.

Functions

login(): A simple function that prints a message indicating the user has successfully logged in. This can be expanded to validate the entered username and password against stored credentials.
Theme Customization
The appearance mode is set to dark using customtkinter.set_appearance_mode('dark').
The color theme is set to dark-blue using customtkinter.set_default_color_theme('dark-blue').

Example

Launch the application, and the login window will appear.
Enter your credentials and click the "Login" button.
A successful login will print a confirmation message to the console.

..................................................................................

CALCULATOR

This is a simple calculator GUI application built using Python's tkinter library. It provides a user-friendly interface to perform basic arithmetic operations like addition, subtraction, multiplication, and division.

Features

Basic Arithmetic Operations: Perform addition, subtraction, multiplication, and division.
Clear and Reset: Clear the current expression with the "C" button.
Equal: Compute and display the result of the expression when the "=" button is pressed.
Decimal Point: Support for decimal numbers using the "." button.

Code Explanation

GUI Layout

The calculator window is created using Tk() from Tkinter and is set to a fixed size of 312x324.
The input field is an Entry widget where users can see the ongoing calculation.
The calculator buttons are created using Button widgets and organized into a grid layout.

Functions

btn_click(item): Adds a button's value to the expression string.
bt_clear(): Clears the current expression.
bt_equal(): Evaluates the expression and displays the result.

Button Functions

Each button calls the btn_click() function with the corresponding value (numbers or operators).
The clear button (C) triggers the bt_clear() function to reset the input field.
The equals button (=) triggers the bt_equal() function to compute the result using Python’s eval() function.

Example

Press numbers and operators: 7, +, 3.
Press = to get the result: 10.
