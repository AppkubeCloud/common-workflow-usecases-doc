**Use Case: User Sign-Up**

**Step 1:**

The user navigates to the Employee Information Portal page by clicking the sign-up "Have an account? Sign Up" link if they are not already on the sign-up page.

The system displays the sign-up form, which includes fields for entering an email, password, and confirmation of password.

**Step 2:**

The user enters their email address in the provided "Email" field.

The system accepts the input and verifies the format of the email address.

**Step 3:**

The user creates a password following the specified criteria: the password must be at least 8 characters long and contain alphanumeric characters and both upper and lowercase letters. The user enters this password in the "Password" field.

The system checks the password to ensure it meets the specified criteria.

**Step 4:**

The user re-enters the password in the "Confirm Password" field to confirm the password.

The system verifies that the password and confirmed password match.

**Step 5:**

The user clicks the "Create Account" button.

If all input fields are filled out correctly, the system creates a new account for the user and sends a confirmation email to the provided email address.

If there are issues with the form, such as mismatched passwords or an invalid email format, the system provides an error message explaining the issue.

**Postconditions:**

If the sign-up process is successful, the user receives a confirmation email and can now log in to the Employee Information Portal using their newly created account.

**Step 1:**

After the user has signed up for an account, they receive an email from the Employee Information Portal with a confirmation link.

The system sends an email to the user’s provided email address containing a confirmation link.

**Step 2:**

The user clicks the confirmation link in the email to verify their email address.

The system confirms the user’s email address and completes the account setup process. The user is notified that their email address has been confirmed.

Alternate Flow - Didn't receive an email?:

If the user doesn't receive the confirmation email, they can click the "Didn't receive an email?" option on the confirmation page.

The system displays an option for the user to request another email confirmation.

**Step 3:**

The user clicks the "Resend Email" button to request the system to resend the email confirmation.

The system sends another confirmation email to the user's provided email address.

**Postconditions:**

Once the user confirms their email address, they can proceed to sign in to the Employee Information Portal using the "Sign In" link.

If the user chooses not to confirm their email address, they may face limitations on their account, such as not being able to fully access portal features.

**Additional Notes:**

If the user doesn't receive the confirmation email and opts to resend the email, the system may implement rate limits or other mechanisms to prevent abuse of the resend feature.


