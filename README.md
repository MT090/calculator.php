# calculator.php
my name is mohammmed temam and this is my php project
# calculator.php
my name is mohammmed temam and this is my php project
Simple PHP Calculator
This project is a simple web-based calculator built using PHP and HTML. It allows users to perform basic arithmetic operations (addition, subtraction, multiplication, and division) on two numbers 

Featts four operations: Addition (+), Subtraction (-), Multiplication (*), and Division (/).
Validates input to prevent division by zero.
Displays the result of the calculation on the same page.
Simple and clean user interface with CSS styling (linked via style.css).
Files
project.php: The main file containing the HTML form and PHP logic for the calculator.
style.css: The stylesheet for styling the calculator interface (not provided in the code but referenced in the HTML).
How It Works
HTML Form:
The form collects two numbers (num1 and num2) and an operation (operation) using a dropdown menu.
The step="any" attribute in the input fields allows decimal numbers.
The form uses the POST method to send data to the same page (project.php) when the "Calculate" button is clicked.
PHP Logic:
When the form is submitted ( $_POST['calculate'] is set), the PHP script retrieves the input values:
$num1: First number.
$num2: Second number.
$operation: Selected operation (add, subtract, multiply, or divide).
A switch statement processes the operation:
Addition: $num1 + $num2
Subtraction: $num1 - $num2
Multiplication: $num1 * $num2
Division: $num1 / $num2, with a check to prevent division by zero.
The result is displayed in an <h3> tag below the form.
Error Handling:
If the second number is zero during division, the script outputs "Cannot divide by zero!".
If an invalid operation is selected, it outputs "Invalid operation selected.".
Accepts two numerical inputs (supports decimal numbers).




