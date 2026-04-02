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
