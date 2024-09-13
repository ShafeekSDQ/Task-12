# Taskten - Registration Form with Validation

## Description

This project contains a simple HTML registration form with fields for user input, such as First Name, Last Name, Email, Phone Number, and Password. The form includes basic styling using CSS and password validation with JavaScript to ensure that both password fields match. When submitted, the form redirects to a confirmation page.

## Features

- **Form Fields**:
  - First Name
  - Last Name
  - Email ID
  - Phone Number
  - Password
  - Confirm Password
- **CSS Styling**: A clean and simple design using external CSS.
- **Password Validation**: Ensures that the password and confirm password fields match before submission.
- **Form Submission**: On successful submission, redirects to `submit.html`, which confirms the registration.

## Setup Instructions

1. **Open the project in VSCodium.**
2. **Start Live Server:**
   - Right-click on `index.html` in the project directory and select **Open with Live Server**.
   - This will launch the registration form in your web browser.
3. **CSS and JavaScript:**
  - CSS code is located in `style.css`.
  - JavaScript for password validation is located in `script.js`.
## File Structure
 1. **index.html:** The main HTML file containing the registration form.
 2. **submit.html**: A simple HTML file displaying a confirmation message.
 3. **style.css:** A CSS file for styling the form.
 4. **script.js:** A JavaScript file for password validation.
## How It Works
 1. Open the registration form (`index.html`) in your web browser.
 2. Fill out all the fields.
 3. Ensure that the password and confirm password fields match.
 4. Upon clicking the Submit button, you will be redirected to `submit.html` with a confirmation message: "You've been registered. Please check your email for details."
## To-Dos
- Implement server-side validation.
- Improve the design with more advanced CSS frameworks.
- Handle form submission with the POST method for security purposes.
