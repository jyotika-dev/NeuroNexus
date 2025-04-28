# Web Form Task

## Overview

This task involved creating a simple and styled web form using HTML and CSS. The form collects basic user information such as full name, contact number, address, company name, email address, department, and gender.

## Files Included

- `index.html`: The HTML file containing the structure and content of the web form.
- `styles.css`: The CSS file containing all the styling rules to visually enhance the web form.

## How to Use

1.  **Save the files:** Ensure that both `index.html` and `styles.css` are saved in the same directory.
2.  **Open in a web browser:** Open the `index.html` file in any modern web browser (Chrome, Firefox, Safari, etc.). The styled web form will be displayed.

## Features

- Clean and user-friendly design.
- Clear labels for each input field.
- Input fields for:
  - Full Name (required)
  - Contact Number (required)
  - Address (optional)
  - Company Name (optional)
  - Email Address (required, with email input type for validation)
  - Department (dropdown select with multiple options)
  - Gender (radio button group with "Male", "Female", and "Prefer not to say" options)
- A styled submit button.
- A simple footer indicating data security.
- Responsive design that adapts to different screen sizes (basic responsiveness implemented).

## Technologies Used

- HTML5: For structuring the content of the web form.
- CSS3: For styling the appearance of the web form, including layout, colors, typography, and responsiveness.

## Notes

- The form currently does not have any backend logic to handle the submitted data. It is a front-end implementation for data collection.
- Basic client-side validation is included for the "Full Name", "Contact Number", and "Email Address" fields using the `required` attribute and the `type="email"` attribute. More advanced validation could be implemented using JavaScript.
- The styling is contained in a separate `styles.css` file for better organization and maintainability.

## Further Improvements (Optional)

- Implement JavaScript for more robust client-side form validation.
- Add backend logic (e.g., using PHP, Python, Node.js) to process and store the submitted form data.
- Enhance the responsiveness for a wider range of devices and screen sizes.
- Consider adding more input types or form elements based on specific requirements.
- Implement accessibility best practices for users with disabilities.
