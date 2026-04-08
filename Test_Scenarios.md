# Test Scenarios – AutomationExercise

## Registration / Sign-Up Module
- Verify user is able to register with valid credentials
- Verify error message is displayed for invalid username and email format
- Verify user cannot proceed with empty input fields
- Verify user is able to edit entered username and email before submission
- Verify user cannot register without entering password
- Verify system handles duplicate user registration properly

## Login Module
- Verify user is able to login with valid credentials
- Verify error message is displayed for invalid login credentials
- Verify user cannot login with empty fields
- Verify user cannot login without prior registration
- Verify user is able to login again with the same credentials after logout

## Product Module
- Verify user is able to view available products
- Verify user is able to add a product to the cart
- Verify user is able to add multiple products to the cart

## Cart Module
- Verify user is able to view items in the cart
- Verify user is able to remove products from the cart
- Verify user is able to continue shopping after adding products to the cart

## Checkout Module
- Verify user cannot proceed to checkout without adding products to the cart
- Verify user is able to proceed to checkout with added products
- Verify user is able to place an order using valid payment details
- Verify error message is displayed when payment details are not provided
- Verify user is able to cancel the order after initiating checkout
