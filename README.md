# Form Validation Application

This is a simple form validation application built with HTML, CSS, and JavaScript. It includes fields for a user's name, email, phone number, and message, along with a submit button. The form validates the input fields to ensure that no fields are left empty before submission.

## Features

- **Form Fields**: Name, Email, Phone, and Message fields.
- **Validation**: Checks if any field is empty and displays an error message if validation fails.
- **User-Friendly Interface**: Clean, responsive design for optimal user experience.

## Technologies Used

- **HTML**: Structure of the form.
- **CSS**: Styling for the form and error messages.
- **JavaScript**: Validation logic to check for empty fields.

## How It Works

1. **Input Validation**: When the user clicks on the submit button, the JavaScript validation function checks each input field.
2. **Error Display**: If any field is left empty, an error message appears beneath the respective field, prompting the user to fill in the missing information.
3. **Submit Button**: The form can only be submitted when all fields contain valid data.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/VinayMalyala/Form_Validation.git
   ```

2. Open the `index.html` file in a web browser to view the form.

## Usage

1. Enter data in each of the fields: Name, Email, Phone, and Message.
2. Click on the "Submit" button.
3. If all fields are filled, the form will submit successfully. If any field is empty, an error message will display below the empty field(s).

## Project Structure

```plaintext
form-validation-app/
├── index.html       # HTML file for the form structure
├── styles.css       # CSS file for styling
└── script.js        # JavaScript file for validation logic
```

## Future Enhancements

- Adding validation for specific formats (e.g., email and phone number patterns).
- Implementing success messages upon form submission.
- Adding backend support for storing submitted data.

