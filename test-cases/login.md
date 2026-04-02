Test Suite: Login
Test Case 1: Login with valid credentials
Description: Validate login with valid credentials
Precondition: User is registered
Steps:
    1. Go to https://the-internet.herokuapp.com/login 
    2. Enter valid username: tomsmith 
    3. Enter valid password: SuperSecretPassword! 
    4. Click Login 
Expected Result:
User is redirected to /secure and sees the message:
“You logged into a secure area!”

Test Case 2: Login with invalid username
Description: Validate login with invalid username
Precondition: User does not exist in the system
Steps:
    1. Go to login page 
    2. Enter invalid username 
    3. Enter valid password 
    4. Click Login 
Expected Result:
System displays the message:
“Your username is invalid!”

Test Case 3: Login with empty password
Description: Validate login when password field is empty
Precondition: User is registered
Steps:
    1. Go to login page 
    2. Enter valid username: tomsmith 
    3. Leave password field empty 
    4. Click Login 
Expected Result:
System should indicate that the password field is required
