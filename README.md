# Interactive Forms

When I did TD this was project 03.

# Technology

- Html, Css, Javascript
- jQuery

# Getting Started:

1. Clone the project from github eg.

- Latest commit `git clone https://github.com/XXXX/XXXX.git`
- Specific commit `git@gist.github.com:XXXX.git`

2. Move into the directory eg. `cd td-0X`
3. Open the index.html file eg. `open -a "Safari" index.html`
   ✅ Open index.html in the browser to run the project.

Expected output:

![Demo Gif](https://github.com/jacob30/gh-assets/blob/main/td-03.png)
_Demo Gif will take a second to load_

# Project Instructions & Features (9 steps)

1. Set focus on the first text field

- When the page loads, give focus to the first text field

2. ”Job Role” section of the form:

- A text field that will be revealed when the "Other" option is selected from the "Job Role" drop down menu.
- Give the field an id of “other-title,” and add the placeholder text of "Your Job Role" to the field.

3. ”T-Shirt Info” section of the form:

- For the T-Shirt color menu, only display the color options that match the design selected in the "Design" menu.
- If the user selects "Theme - JS Puns" then the color menu should only display "Cornflower Blue," "Dark Slate Grey," and "Gold."
- If the user selects "Theme - I ♥ JS" then the color menu should only display "Tomato," "Steel Blue," and "Dim Grey."

4. ”Register for Activities” section of the form:

- Some events are at the same time as others. If the user selects a workshop, don't allow selection of a workshop at the same date and time -- you should disable the checkbox and visually indicate that the workshop in the competing time slot isn't available.
- When a user unchecks an activity, make sure that competing activities (if there are any) are no longer disabled.
- As a user selects activities, a running total should display below the list of checkboxes. For example, if the user selects "Main Conference", then Total: $200 should appear. If they add 1 workshop, the total should change to Total: $300.

5. Payment Info section of the form:
   Display payment sections based on the payment option chosen in the select menu
   The "Credit Card" payment option should be selected by default, display the #credit-card div, and hide the "Paypal" and "Bitcoin information.
   When a user selects the "PayPal" payment option, the Paypal information should display, and the credit card and “Bitcoin” information should be hidden.
   When a user selects the "Bitcoin" payment option, the Bitcoin information should display, and the credit card and “PayPal” information should be hidden.

6. Form validation:
   If any of the following validation errors exist, prevent the user from submitting the form:
   Name field can't be blank
   Email field must be a validly formatted e-mail address (you don't have to check that it's a real e-mail address, just that it's formatted like one: dave@teamtreehouse.com for example.
   Must select at least one checkbox under the "Register for Activities" section of the form.
   If the selected payment option is "Credit Card," make sure the user has supplied a credit card number, a zip code, and a 3 number CVV value before the form can be submitted.
   Credit card field should only accept a number between 13 and 16 digits
   The zipcode field should accept a 5-digit number
   The CVV should only accept a number that is exactly 3 digits long

7. Form validation messages:
   Provide some kind of indication when there’s a validation error. The field’s borders could turn red, for example, or a message could appear near the field or at the top of the form
   There should be an error indication for the name field, email field, “Register for Activities” checkboxes, credit card number, zip code, and CVV

8. When JavaScript is switched off or unavailable, the user should still have access to all form fields and payment information. For example, the “Other” text field in the "Job Role" menu should be visible on the page when JavaScript is switched off, and all information for Bitcoin, Paypal or Credit Card payments should be visible.

9. Before you submit your project for review, make sure you can check off all of the items on the Student Project Submission Checklist. The checklist is designed to help you make sure you’ve met the grading requirements and that your project is complete and ready to be submitted!
