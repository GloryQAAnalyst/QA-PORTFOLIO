# User Login
As a registered customer, I want to log into my account on DemoBlaze So that I can access my shopping features.
# Scenario 1: Open Login Modal
Given the user is on the homepage When the user clicks the “Log In” button Then the login modal should be displayed
# Scenario 2: Successful Login
Given the login modal is displayed When the user enters valid login credentials And clicks the “Log In” button Then the user should be logged in 
successfully.
# Scenario 3: Invalid Login
Given the login modal is displayed When the user enters invalid username or password Then an error message should be displayed 
And the username should appear on the navigation bar
# Scenario 4: Empty Credentials
Given the login modal is displayed When the user leaves required fields empty And clicks the “Log In” button Then the login 
should not be successful And a validation message should appear
