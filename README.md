🔹 Features

Natural Language Input: Accepts math problems in plain English.

Regex Parsing: Uses regular expressions to extract numbers and operators.

Basic Operations: Supports addition, subtraction, multiplication, and division.

Error Handling:

Empty input → shows error.

Invalid format → shows error.

Division by zero → handled gracefully.

GUI Interface:

Built with Tkinter.

Simple interface with input box, result display, and buttons for Calculate and Clear.

Keyboard Support: Pressing Enter key also triggers calculation.

🔹 How It Works (Step-by-Step)

User enters a calculation in plain English or symbols (5+3, add 2 and 6, 10 divided by 5).

Input text is converted into a mathematical expression by replacing words (plus → +, times → *, etc.).

A regex pattern identifies numbers and operator.

Expression is evaluated and result is displayed on the GUI.

Errors are shown via Tkinter message boxes.

🔹 Why It’s Useful

Demonstrates applied NLP with regex in a simple project.

Good example of combining GUI (Tkinter) + Regex + Basic NLP.

Beginner-friendly but highlights concepts of text parsing, input validation, and event-driven programming.

🔹 Applications

🎓 Educational Tool – Helps beginners understand how NLP can be applied in real-world use cases.

🖥 Mini Productivity App – Can be extended into a smart calculator with advanced parsing.

🤖 NLP Demo – A small project that demonstrates how machines can "understand" math instructions in human language.

✅ Quick Summary Line

A GUI-based NLP Calculator built with Python Tkinter that parses natural language math queries using regex and computes results with error handling.
