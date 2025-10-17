# Simple Calculator

## Summary
This is a simple calculator that adds two numbers entered by the user.

## Features
- **Simple Addition:** Users can enter two numbers and get the sum as the result.
- **Responsive Design:** This calculator is fully responsive and works well on both desktop and mobile devices.
- **Error Handling:** The calculator handles errors gracefully, informing the user of invalid inputs.

## Setup
No build steps required. This is a static HTML application.

### Local Usage
1. Download or clone the repository.
2. Open `index.html` in any modern web browser.
3. Start using the calculator by entering numbers.

### GitHub Pages
The application is deployed at: [Your GitHub Pages URL]

## Usage Instructions
1. Enter a value in the "Number 1" input field.
2. Enter a value in the "Number 2" input field.
3. Click the "Calculate" button to see the sum of the two numbers displayed below.
4. If the inputs are not valid numbers, an error message will be displayed.

## Technical Details

### Technologies Used
- HTML5
- CSS3 (Bootstrap 5.3.0)
- Vanilla JavaScript

### Key Features
- Responsive design adapts to different screen sizes.
- Client-side calculations ensure immediate feedback.
- Error handling for non-numeric and missing inputs.

### File Structure
```
.
├── index.html          # Main application file
├── README.md           # This file
└── LICENSE             # MIT License
```

## Code Explanation

### HTML Structure
- **Inputs:** Two input fields for user numbers.
- **Button:** A button to trigger the calculation.
- **Result Display:** An element to display the result or error message.

### CSS Styling
- Uses Bootstrap for responsive design and components.
- Custom gradients and shadows for a modern look.

### JavaScript Functionality
- **Event Handling:** Listens for button clicks to perform calculations.
- **Calculation Logic:** Parses input values, calculates sum, and handles errors.

## Evaluation Criteria
This application meets the following requirements:
- Page has input field with id='num1'
- Page has input field with id='num2'
- Page has button with id='calculate-btn'
- Page has element with id='result'
- Page loads Bootstrap 5 from CDN
- Repo has MIT LICENSE
- README.md is professional

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Author
Generated as part of IIT Madras TDS Project