# Zentrades-Smartserve-Coding-Assignment-Task-4
# User Authentication HTML Form

This HTML file provides a simple user authentication form with specific functionalities implemented using JavaScript. The form includes a username field and a password field with the following requirements:

## User Name Field:
- Accepts only email format.
- Validation is performed through JavaScript.

## Password Field:
- A masked field for enhanced security.
- Entering the password as - "SmartServTest@123" redirects the user to a dashboard page.
- Any other password is incorrect

## Forgot Your Password

Clicking on the "Forgot your password" link will open your default email client to send an email for resetting the password. The email will be addressed to support@smartserv.io.

## Dashboard Page
<img width="1375" alt="Screenshot 2024-03-20 at 4 13 27 PM" src="https://github.com/abhik144/Zentrades-Smartserve-Coding-Assignment-Task-4/assets/87299462/4a91f0d8-b6d0-44c8-9b81-3609cef7bc9d">
<img width="1377" alt="Screenshot 2024-03-20 at 4 10 57 PM" src="https://github.com/abhik144/Zentrades-Smartserve-Coding-Assignment-Task-4/assets/87299462/fe872f5c-53ea-419a-a1ed-e5533e7e9f62">


The dashboard page is designed with actual components, avoiding the use of images. All components, including charts and dropdowns, are implemented using HTML, CSS, and JavaScript. This approach ensures a lightweight and responsive dashboard experience.

## Usage:

1. Clone the repository to your local machine & download the HTML file (e.g., `index.html`) to your local machine.
2. Open the file in a web browser to use the authentication form.   
3. Click on the "Forgot your password" link to initiate the password reset process.
4. Access the `Page2.html` file to explore the dashboard components using "Abhi@123" as password.

## Implementation Details:

- The HTML file includes a form element with input fields for username and password.
- JavaScript is embedded within the HTML to handle form validation.
- The username field checks if the entered value follows the email format.
- The password field masks the input to enhance security.
- Password validation ensures the inclusion of at least one uppercase letter, one number, and disallows special characters except for @.
 
