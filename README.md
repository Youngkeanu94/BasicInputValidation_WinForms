This C# code represents a simple Windows Forms application designed to demonstrate basic input validation and user interaction. Here's a breakdown of its functionality:

Form Initialization: The Form1 class initializes a Windows Form with various components (presumably including text boxes and labels, although the details of InitializeComponent are not provided).

Age Validation (button1_Click):
When a button (likely labeled for age validation) is clicked, the program checks the text input from textBox1 (presumably for age input).
It validates whether the entered age is between 5 and 18 years.
Based on this validation, it updates label2 with either a success message displaying the entered age or an error message for an invalid age.
Email Validation (button2_Click):

Another button click event validates the text input from textBox2 (presumably for email input).
It checks if the entered text contains an '@' symbol to validate it as an email address.
Accordingly, it updates label3 with either the entered email or an error message indicating the requirement of an '@' symbol.
