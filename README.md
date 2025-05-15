# Simple-Calculator
Simple Calculator
QuickCalc - Simple Calculator
QuickCalc is a lightweight, modern calculator web application that performs basic arithmetic operations. It features a sleek glassmorphism design, clickable buttons, keyboard input support, and a responsive layout. Built with HTML, CSS, and JavaScript, it is ready for deployment on GitHub Pages without any build tools.
Features

Clickable Buttons: Includes buttons for digits (0-9), operators (+, -, ×, ÷), parentheses, decimal point, clear, backspace, and equals.
Keyboard Input Support: Supports number keys, operators, Enter (calculate), Backspace (delete), Escape (clear), and parentheses.
Modern Glassmorphism Design: Translucent buttons and calculator container with blur effects, set against a vibrant gradient background.
Responsive Layout: Uses CSS Grid for button layout and Flexbox for centering, with mobile-friendly adjustments for smaller screens.
Single HTML File: Structured with one index.html, separate style.css, and script.js for clean organization.

Project Structure
quickcalc/
├── index.html
├── style.css
├── script.js
└── README.md


index.html: Main HTML file with the calculator structure.
style.css: CSS with glassmorphism styling, responsive design, and hover effects.
script.js: JavaScript for handling button clicks, keyboard input, and calculations.

Setup

Clone the Repository:
git clone https://github.com/your-username/quickcalc.git
cd quickcalc


Open Locally:

Open index.html in a web browser to run the calculator locally.
No build tools or dependencies are required.



Deployment
QuickCalc is designed for easy deployment on GitHub Pages:

Push to GitHub:

Create a GitHub repository (e.g., quickcalc).
Push all files to the repository:git add .
git commit -m "Initial commit"
git push origin main




Enable GitHub Pages:

Go to the repository settings on GitHub.
Navigate to the "Pages" section.
Set the source to the main branch and root directory.
Save, and GitHub Pages will provide a URL (e.g., https://your-username.github.io/quickcalc).


Access the Calculator:

Visit the GitHub Pages URL to use the calculator.



Usage

Add Input: Click buttons or use the keyboard to input numbers, operators, or parentheses.
Calculate: Press the "=" button or Enter key to evaluate the expression.
Clear: Press the "C" button or Escape key to reset the display.
Delete: Press the backspace button (←) or Backspace key to remove the last character.
Responsive Design: The calculator adjusts for mobile devices with smaller fonts and tighter spacing.

Technologies Used

HTML: Single file for structure.
CSS: Glassmorphism styling with CSS Grid and Flexbox.
JavaScript: Handles logic for calculations and input.

Notes

The calculator uses eval() for simplicity, with error handling for invalid expressions.
The backspace button uses a modern left arrow icon (←) for a clean look.
No external dependencies or build tools are required, making it lightweight and portable.

License
This project is open-source and available under the MIT License.
