# JS Age Calculator

## Overview

The **JS Age Calculator** is a web application designed to calculate a person's age based on their date of birth. This project, built using JavaScript, HTML, and CSS, demonstrates essential front-end development skills and provides a practical tool for users to determine their exact age in years, months, and days.
[TRY NOW!](https://qyuzet.github.io/js-age-calculator/)


![image](https://github.com/Qyuzet/js-age-calculator/assets/93258081/8fbf2ae3-3b29-483c-a67e-fb6e3acb4a85)


## Features

- **Date Input**: Users can enter their date of birth.
- **Age Calculation**: The app calculates the user's age in years, months, and days.
- **Responsive Design**: Accessible on various devices, including desktops and mobiles.

## Installation

To run the app locally:

1. Clone the repository:
    ```bash
    git clone https://github.com/Qyuzet/js-age-calculator.git
    ```
2. Navigate to the project directory:
    ```bash
    cd js-age-calculator
    ```
3. Open `index.html` in your preferred web browser.

## File Structure

- **index.html**: The main HTML file containing the structure of the app.
- **style.css**: The CSS file providing the styling for the app.
- **scripts.js**: The JavaScript file containing the logic and functionality of the app.

## Usage

1. Open `index.html` in a web browser.
2. Enter the date of birth in the input field.
3. Click "Calculate" to display the age in years, months, and days.

### Code Explanation

#### HTML (`index.html`)

The HTML file sets up the basic structure of the age calculator, including input fields for the date of birth and a button to calculate the age.

#### CSS (`style.css`)

The CSS file ensures the app has a clean and modern look. It styles the input fields, button, and the result display area.

#### JavaScript (`scripts.js`)

The JavaScript file implements the core functionality of the app. Key functions and features include:

- **Event Listeners**: Handling user interactions such as entering the date and clicking the button.
- **Age Calculation**:
  - **calculateAge()**: Computes the age based on the entered date of birth, breaking down the result into years, months, and days.
  - **getDaysinMonth()**: Helper function to determine the number of days in a given month and year.

### Detailed Explanation

#### Age Calculation
The `calculateAge()` function determines the difference between the current date and the entered date of birth. It breaks down the result into years, months, and days to provide a detailed age calculation. Here's how it works:

1. **Retrieve Input**: Get the user's date of birth from the input field.
2. **Calculate Difference**: Compute the difference between the current date and the date of birth.
3. **Adjust Values**: Adjust the month and day values to ensure accurate calculations.
4. **Display Result**: Update the HTML to show the calculated age.

## Responsive Design

The app is designed to be fully responsive, ensuring it works seamlessly on various devices, including desktops, tablets, and mobile phones. The use of CSS Flexbox and media queries ensures that the layout adjusts appropriately to different screen sizes.

## Academic Insights

This project demonstrates key concepts in web development, including DOM manipulation, event handling, and date calculations. It serves as a practical example for computer science students to understand how front-end technologies can be integrated to create functional web applications. Through this project, students can learn:

- **HTML5**: Structuring web content.
- **CSS3**: Styling web pages.
- **JavaScript**: Adding interactivity and handling data.
- **Responsive Design**: Ensuring usability across different devices.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](https://github.com/Qyuzet/js-age-calculator/blob/main/LICENSE) file for details.

## Contact

For any questions or suggestions, please contact Riki Awal Syahputra at [riqyuzet@gmail.com](mailto:riqyuzet@gmail.com).

## Live Demo

You can try the app live at [JS Age Calculator Demo](https://qyuzet.github.io/js-age-calculator/).

For more details and to view the code, visit the [GitHub repository](https://github.com/Qyuzet/js-age-calculator).
