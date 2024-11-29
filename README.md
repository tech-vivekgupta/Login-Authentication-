# Login-Authentication-
Purpose: This page provides a Login and SignUp interface for users to authenticate themselves. Users can switch between the two forms using toggle buttons.

The provided React component represents a simple authentication page with the following functionalities and features:

Overview
Purpose:
This page provides a Login and SignUp interface for users to authenticate themselves. Users can switch between the two forms using toggle buttons.
Key Features
Toggle Between Login and SignUp Forms:

A state variable isLogin is used to determine whether the Login or SignUp form is displayed.
Clicking the Login or SignUp button toggles the isLogin state, switching between the forms dynamically.
Login Form:

Contains fields for:
Email: A placeholder input for the user's email.
Password: A placeholder input for the user's password.
Includes a "Forgot Password" link.
A button to submit the login details.
SignUp Form:

Contains fields for:
Email or Phone: A placeholder input for either an email or phone number.
Password: A placeholder input for setting a password.
Confirm Password: A placeholder input to confirm the password.
Includes a button to submit the signup details.
Interactive Elements:

A toggle link inside the Login Form to quickly switch to the SignUp Form.
Active button highlighting for the currently selected form using dynamic class names (active).
State Management
The state is managed using the React useState hook:
isLogin:
A boolean state (true for Login form, false for SignUp form).
Dynamically changes the UI to display the corresponding form.
CSS Classes and Styling
The following classes suggest styling details:

.container: Likely used to center and structure the main component.
.form-container: Wraps both forms and the toggle buttons.
.form-toggle: Aligns and styles the toggle buttons.
.form: Structures each individual form.
.active: Highlights the active toggle button to indicate the currently selected form.
Code Behavior
Initial Load:

By default, the isLogin state is set to true, displaying the Login Form.
Switching Forms:

Clicking the SignUp button sets isLogin to false, replacing the Login form with the SignUp Form.
Clicking the Login button reverses the action.
Interactivity:

The onClick handlers ensure the state updates dynamically, leading to a smooth UI toggle.
