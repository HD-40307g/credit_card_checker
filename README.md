# Credit Card Checker

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
The **Credit Card Checker** is a JavaScript-based tool that validates credit card numbers using the Luhn algorithm. This project ensures that credit card numbers are syntactically correct, which is essential for payment processing systems and educational purposes.

## Features
- **Luhn Algorithm Implementation**: Validates credit card numbers for correctness.
- **Batch Processing**: Handles multiple credit card numbers simultaneously.
- **Credit Card Identification**: Determines the type of credit card based on the number prefix.

## Technologies Used
- **JavaScript**: Core programming language for the tool.

## Getting Started
To get a local copy up and running, follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/HD-40307g/credit_card_checker.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd credit_card_checker
   ```

## Usage
1. **Include the Script**: Ensure the `CreditCardChecker.js` file is included in your project.
2. **Validate a Credit Card Number**:
   ```javascript
   const isValid = validateCreditCard('4532015112830366');
   console.log(isValid); // Outputs: true or false
   ```
3. **Identify Credit Card Type**:
   ```javascript
   const cardType = getCardType('4532015112830366');
   console.log(cardType); // Outputs: 'Visa', 'MasterCard', etc.
   ```

## Testing
To test the functionality:
1. **Run the Script**: Execute the JavaScript file in a Node.js environment or include it in an HTML file and open it in a browser.
2. **Check Console Output**: Review the console for validation results and ensure accuracy.

## Contributing
Contributions are welcome! To contribute:
1. **Fork the Repository**.
2. **Create a New Branch**:
   ```bash
   git checkout -b feature/YourFeatureName
   ```
3. **Commit Your Changes**:
   ```bash
   git commit -m 'Add Your Feature'
   ```
4. **Push to the Branch**:
   ```bash
   git push origin feature/YourFeatureName
   ```
5. **Open a Pull Request**.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For questions or suggestions, please open an issue in this repository.
