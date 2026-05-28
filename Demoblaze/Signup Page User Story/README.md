User Registration on DemoBlaze As a new customer, I want to create an account on Demoblaze.com So that I can log in 
and purchase products.
# scenario 1: Successful Sign
Given the user is on the homepage When the user clicks the “Sign Up” button Then the sign-up modal should be displayed
# Scenario 2: Successful Account Creation
Given the sign-up modal is displayed When the user enters a valid username and password and clicks “Sign Up” Then the account should be 
created successfully And a success message should be displayed
# Scenario 3: Existing Username
Given the sign-up modal is displayed When the user enters an already existing username Then an error message should be displayed
# Scenario 4: Empty Fields
Given the sign-up modal is displayed When the user leaves the username or password field empty and clicks “Sign Up” Then the system should prevent account creation And an appropriate validation message should be displayed
