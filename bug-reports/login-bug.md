Bug ID: 01
Title: Incorrect error message when password field is empty
Reported by: Ignacio Correa
Environment: Ubuntu / Chrome
Severity: Medium
Priority: Medium
Description:
When the password field is left empty during login, the system shows an incorrect error message.
Steps to Reproduce:
    1. Go to https://the-internet.herokuapp.com/login 
    2. Enter valid username: tomsmith 
    3. Leave password field empty 
    4. Click Login 
Expected Result:
System should indicate that the password field is required
Actual Result:
System displays: “Your password is invalid!”
