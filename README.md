# Telephone Number Validator

A JavaScript application that checks if a given string is a valid US telephone number. The validator ensures the string follows the various formats accepted in the United States.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Examples of Valid Telephone Numbers](#examples-of-valid-telephone-numbers)
- [Examples of Invalid Telephone Numbers](#examples-of-invalid-telephone-numbers)

## Features

- Validates US telephone numbers in various formats.
- Handles different formats including parentheses, hyphens, spaces, and country codes.
- Returns a boolean value indicating whether the number is valid or not.

## Technologies Used

- **JavaScript (ES6)**: Core logic for validating telephone numbers.
- **Regex**: Utilized for pattern matching and validation of the number format.

## Setup and Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/telephone-number-validator.git
    ```
2. Navigate to the project directory:
    ```bash
    cd telephone-number-validator
    ```
3. Open the `index.html` file in your browser to test the validator locally.

## Usage

1. Enter a US telephone number in the input field.
2. Click the "Validate" button or press Enter.
3. The application will display a message indicating whether the number is valid or invalid.

## Project Structure

```plaintext
telephone-number-validator/
│
├── index.html          # The main HTML file
├── styles.css          # The CSS file for styling
└── script.js           # JavaScript file containing the validator logic
```

## Examples of Valid Telephone Numbers

- `555-555-5555`
- `(555) 555-5555`
- `555 555 5555`
- `5555555555`
- `1 555 555 5555`
  

## Examples of Invalid Telephone Numbers

- `123-abc-4567`
- `555-5555`
- `55555555555`
- `555-5555-5555`
- `(555)555-5555`
