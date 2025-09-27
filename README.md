# javascript-calculator
A simple calculator built with HTML, CSS, and JavaScript
JavaScript Calculator

A simple web-based calculator built with HTML, CSS, and JavaScript. It performs basic arithmetic operations and provides a user-friendly interface.

Features

Basic arithmetic: +, -, *, /

Decimal support: .

Percentage calculation: %

Clear (AC) and delete (DEL) functions

Responsive layout

Demo

Open index.html in your browser to use the calculator.

How to Use

Clone the repository:

git clone https://github.com/yourusername/calculator.git


Navigate to the project folder and open index.html in a browser.

Click the buttons to perform calculations.

File Structure
calculator/
│
├── index.html      # HTML structure
├── style.css       # Styling
└── script.js       # JavaScript functionality (or inline in HTML)

How It Works

Each button is a <div> inside the #keys container.

Clicking a button triggers the mycalculator function:

AC → Clears all input

DEL → Deletes the last character

= → Evaluates the expression

Numbers/operators → Appends to current input

Example Usage
Sequence	Result
7 + 5 =	12
10 * 2 =	20
50 % =	0.5
Notes

Uses JavaScript eval() for calculations. Not safe for untrusted input in production.

Styling is minimal and can be customized in style.css.

License

This project is open source and free to use.
