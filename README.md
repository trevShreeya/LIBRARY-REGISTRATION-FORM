# LIBRARY-REGISTRATION-FORM
Developed a project registration of a student for library card and validate the fields using Java Script. (Assume fields for students’ registration)
This project is a simple web application designed to facilitate the registration process for students obtaining library cards.
It features a user-friendly interface where students can input their personal details such as name, address, roll number, branch, section, current year, phone number, and email address.
The form includes basic validation to ensure that the entered information is correct and complete.



# COMPONENTS
##  HTML Structure:
The HTML document starts with the <!DOCTYPE html> declaration, specifying the document type and language.
Inside the <head> section, metadata like character set, viewport settings, and title are defined.
The <style> tag contains CSS rules for styling the elements.
The <script> tag contains JavaScript functions for form validation.
In the <body> section, the form for library card registration is defined, along with error message display area.

## CSS Styling:
The CSS styles define the layout and appearance of various elements in the form.
The body element is set to flexbox layout, centered horizontally, and aligned to the top.
The h2 heading is centered horizontally with no margin at the top.
Form elements are styled for width, padding, and margin to maintain consistency and spacing.
Error messages are styled to appear in red and centered horizontally.

## JavaScript Validation:
The formValidator function is called when the form is submitted. It checks all input fields for validity.
Each input field is validated by a corresponding validation function (e.g., Name, Address, Rollno, etc.).
Each validation function checks if the input meets certain criteria (e.g., only letters, only numbers, valid email format, etc.).
If any validation fails, an error message is displayed, and focus is set back to the input field for correction.
If all validations pass, the form is submitted.

## HTML Form:
The form contains input fields for name, address, roll number, branch, section, current year, phone number, and email.
Each input field is associated with a corresponding <label> for better accessibility.
Required attribute is added to ensure these fields cannot be left blank.
A submit button is provided at the end of the form.

Overall, this code creates a responsive library card registration form with client-side validation using JavaScript. It ensures that users provide correct and complete information before submitting the form.

# java form validation program
