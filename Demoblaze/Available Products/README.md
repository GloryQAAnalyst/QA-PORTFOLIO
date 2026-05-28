# Description
As a customer I want to view products displayed on the homepage So that I can explore items available for purchase
# Scenario 1: Homepage loads successfully
Given the user navigates to DemoBlaze When the homepage finishes loading Then the user should see the product listings displayed And the navigation menu should be visible And the categories section should be visible.
# Scenario 2: User views a product card
Given the homepage is displayed When the user looks at a product card Then the product name should be visible And the product price should be visible And the product image should be displayed.
# Scenario 3: User clicks a product
Given the user is on the homepage When the user clicks on a product Then the user should be redirected to the product details page.
