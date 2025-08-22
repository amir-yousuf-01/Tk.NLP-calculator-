NLP Calculator — Summary

Launch UI

Opens a minimal Tkinter window with: input entry, result label, and two buttons — Calculate and Clear.

User Input

You type a short math request in words or symbols, e.g. add 5 and 7, 10 divided by 2, or 6*4.

Normalize Text

The app lowercases the input and trims extra spaces to make parsing predictable.

Map Phrases → Operators

Replaces words with symbols:

plus/add → +

minus/subtract → -

times/multiplied by → *

divide/divided by → /

Parse with Regex

Looks for the simple pattern number operator number.

Supports integers and decimals (e.g., 3, 7.5).

Validate Match

If the pattern isn’t found, it shows a friendly message explaining acceptable formats.

Convert Numbers

Extracted operands are converted to float so decimals work consistently.

Evaluate Safely

Performs exactly one binary operation (+, -, *, /).

Checks for division by zero and stops with a clear warning if it occurs.

Format Result

Rounds/prints to two decimal places for a clean, consistent display.

Show Output

Displays the answer in the main result label and an info dialog box.

Pressing Enter also triggers Calculate.

Clear / Reset

Clear empties the entry and resets the result label, ready for the next calc.

Error Handling (What it catches)

Empty input

Unparsable text (doesn’t match pattern)

Invalid numbers

Division by zero
→ Each case returns a short, actionable message.

What It Supports

Natural phrases (add 5 and 7, divide 10 by 2)

Symbolic forms (6*4, 9-2, 3.5+1.2)

Easy to Extend

Add patterns like “subtract X from Y”

Support negatives, percentages

Allow chained operations with precedence

Broaden language/phrasing coverage
