
Simple Java Calculator
This project is a simple calculator application built using Java Swing for the GUI. It supports basic arithmetic operations such as addition, subtraction, multiplication, division, and percentage calculation.

*Features*
Basic Arithmetic Operations: Perform addition, subtraction, multiplication, division, and percentage calculations.
Backspace Function: Remove the last entered character.
Clear Function: Clear the entire input field.
Decimal Point Support: Handle floating-point numbers in calculations.
Installation
To run this application, ensure you have Java Development Kit (JDK) installed on your machine. You can download it from here.

*Clone the repository:*

bash
Copy code
git clone (https://github.com/AdithyaRathnayka/Calculator/)
cd Calculator/src/cal.java
Compile the Java file:

bash
Copy code
javac cal.java
Run the application:

bash
Copy code
java cal
Usage
The calculator has a graphical user interface (GUI) with buttons for digits (0-9), operations (+, -, *, /, %), a decimal point (.), a backspace button, and a clear button.

Operations:
Addition: Click on the numbers you want to add and press the + button. Enter the second number and press =.
Subtraction: Click on the numbers you want to subtract and press the - button. Enter the second number and press =.
Multiplication: Click on the numbers you want to multiply and press the * button. Enter the second number and press =.
Division: Click on the numbers you want to divide and press the / button. Enter the second number and press =.
Percentage: Click on the number and press the % button to get the percentage.
Special Buttons:
Backspace (←): Removes the last digit entered.
Clear (C): Clears the input field.
Equal (=): Computes the result of the entered arithmetic operation.
Code Overview
The main components of the calculator are:

JFrame: The main window.
JTextField: Input field to display the entered numbers and results.
JButton: Buttons for digits, operations, and special functions.

![Screenshot (582)](https://github.com/AdithyaRathnayka/Calculator/assets/99322651/4e8fdfc5-d3bc-48a5-89f4-9e6818bfa077)


Key Sections of the Code:
Initializing the Frame: Setting up the main window properties.
TextField: Adding a text field to display the numbers and results.
Buttons: Adding buttons for digits, operations, backspace, clear, and equal. Each button has an ActionListener to handle the respective actions.
Event Handling: Handling the actions for each button to perform the necessary calculations and updates on the text field.
