# Add to Cart User Story 
As a logged-in customer, I want to add products to my cart on DemoBlaze So that I can purchase them later.
# Scenario 2: Add Product Successfully
Given the user is on the product details page When the user clicks the “Add to Cart” button Then the product
should be added to the cart successfully And a confirmation message should be displayed
# Verify Product in Cart
Given the product has been added to the cart When the user navigates to the cart page Then the added product should be displayed 
in the cart And the product name, price, and total amount should be visible
# Remove Product from Cart
Given the cart contains a product When the user clicks the “Delete” button for the product Then the product should be removed from the cart successfully

