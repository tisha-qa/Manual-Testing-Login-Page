Login Page Manual Testing

1. Project Objective

To test the login page and verify that it works correctly with valid and invalid credentials.

2. Test Cases

TC_LOGIN_001: Login with Valid Credentials

- Steps: Enter valid username and password, then click Login.
- Expected Result: User should log in successfully.
- Actual Result: Products page opened successfully after login.
- Status: Pass

TC_LOGIN_002: Login with Invalid Password

- Steps: Enter a valid an invalid password, then click Login.
- Expected Result: An appropriate error message should appear.
- Actual Result: Error message appeared and login was unsuccessful.
- Status: Pass

TC_LOGIN_003: Login with Invalid Username

- Steps: Enter an invalid username, and a valid password then click Login.
- Expected Result:  an appropriate error message should appear.
- Actual Result: Error message appeared and login was unseuccessful.
- Status: Pass

TC_LOGIN_004: Submit Empty Fields

- Steps: Leave both username and password empty, then click Login.
- Expected Result: An appropriate validation error message should appear.
- Actual Result: Error message appeared and login was unsuccessful.
- Status: Pass

TC_LOGIN_005: Password Masking

- Steps: Enter a password in the password field.
- Expected Result: The password should be masked and displayed as dots or bullets.
- Status: Pass

TC_LOGIN_006: Logout

- Steps: Log in successfully and click Logout.
- Expected Result: The user should be logged out successfully.
- Status: Not Executed

3. Test Summary

- Total Test Cases: 6
- Executed: 0
- Passed: 0
- Failed: 0
- Blocked: 0

