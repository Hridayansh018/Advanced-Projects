# PROJECT 1

1. **Imports**:
   - The script begins by importing necessary modules from the Tkinter library. Tkinter is a standard GUI library for Python.

2. **Global Variables**:
   - Two global variables `count` and `eq_text` are initialized. `count` is used to track the number of login attempts, while `eq_text` stores the expression entered in the calculator.

3. **Button Press Functions**:
   - Several functions are defined to handle button presses in the calculator interface. `button_press` appends the pressed button's value to the expression text, `backspace` removes the last character, `clear` clears the expression, and `equals` evaluates the expression and displays the result.

4. **Login Functionality**:
   - The `login` function is defined to handle the login process. It retrieves the username and password entered by the user. If the fields are empty, it displays a message box asking for valid details. If the correct credentials are entered, it opens a new window with a "LOGIN SUCCESSFUL" label and a button to open the calculator.

5. **Calculator Window**:
   - The `click` function is defined to open the calculator window when the login is successful. It creates a new Tkinter window (`Tk`) and sets up the calculator interface with buttons for numbers, operators, and other functionalities.

6. **Main Window Setup**:
   - The main window (`abs_window`) is created with a size of 300x300 pixels. A background image is loaded and displayed on the window. Entry fields for username and password are placed on the window, along with a login button.

7. **Main Loop**:
   - The script enters the main event loop (`mainloop()`) to display the window and handle user interactions. This loop listens for user actions such as button clicks and updates the GUI accordingly.
   
```
In summary, the code sets up a GUI login interface with Tkinter,
where users can enter their credentials. If the login is successful,
it opens a calculator window where users can perform basic arithmetic operations.
The script utilizes functions to handle user inputs and update the interface dynamically.
```
