# Test Scenarios – AutomationExercise

# Registration Module

- Verify user is able to register with valid details  
- Verify success message is displayed after successful registration  
- Verify error message is displayed for invalid email format  
- Verify user cannot register with empty mandatory fields  
- Verify user cannot register without entering password  
- Verify user cannot register without entering email  
- Verify user is able to edit entered details before submission  
- Verify system does not allow duplicate email registration  

### ▶ TITLE SELECTION
- Verify user is able to select either "Mr" or "Mrs" radio button  
- Verify user cannot select both radio buttons at the same time  
- Verify validation message is displayed if no radio button is selected (if mandatory)  

### ▶ Name Fields
- Verify user is able to enter first name and last name  
- Verify validation message is displayed for empty name fields (if mandatory)  

### ▶ Password Field
- Verify user is able to enter password  
- Verify validation message is displayed for empty password field  
- Verify password meets required validation rules (if any)  

### ▶ Date of Birth
- Verify user is able to select day, month, and year  
- Verify system behavior when date fields are left empty (if optional/mandatory)  

### ▶ Checkbox Options
- Verify user is able to select newsletter checkbox  
- Verify user is able to register without selecting newsletter checkbox  
- Verify user is able to select special offers checkbox  
- Verify user is able to register without selecting special offers checkbox  

### ▶ Address Details
- Verify user is able to enter address details  
- Verify validation message is displayed for empty address field (if mandatory)  

### ▶ Country Dropdown
- Verify user is able to select a country from dropdown  
- Verify only one country can be selected at a time  

### ▶ Location Fields
- Verify user is able to enter state, city, and zipcode  
- Verify validation message is displayed for empty fields (if mandatory)  

### ▶ Mobile Number
- Verify user is able to enter mobile number  
- Verify validation message is displayed for empty mobile number field  
- Verify error message is displayed for invalid mobile number format  

### ▶ Final Submission
- Verify account is created successfully when all mandatory fields are filled
  
# Login Module
- Verify user is able to login with valid credentials
- Verify by success message is displayed for valid credentials
- Verify user is able to login with invalid credentials
- Verify error message is displayed for invalid login credentials
- Verify user can login with empty fields
- Verify user can login without prior registration
- Verify user is able to login again with the same credentials after logout

# Product Module

- Verify user is able to view all available products  
- Verify product details are displayed correctly  
- Verify user is able to add a product to the cart  
- Verify user is able to add multiple products to the cart  
- Verify user is able to add the same product multiple times (quantity increase)  

### ▶ Review Functionality
- Verify user is able to write and submit a product review  
- Verify review submission is successful with valid inputs  
- Verify error message is displayed when submitting review with empty fields  

### ▶ Additional Features
- Verify user is able to share the product (if share option is available)
- Verify by success message is displayed after adding the product to cart
- Verify product image is displayed correctly
  
# Cart Module
- Verify cart displays all added products correctly  
- Verify user is able to remove products from the cart  
- Verify cart is updated after removing a product  
- Verify user is able to continue shopping from the cart page  
- Verify correct product details (name, quantity, price) are displayed  
- Verify total amount is calculated correctly for multiple products
  
# Checkout Module
- Verify user cannot proceed to checkout without adding products to the cart  
- Verify user is able to proceed to checkout with added products  
- Verify user is redirected to login page when trying to checkout without login (if applicable)  

### ▶ Payment Functionality
- Verify user is able to place an order using valid payment details  
- Verify error message is displayed when payment details are not provided  
- Verify error message is displayed for invalid payment details  
- Verify user cannot place an order without mandatory payment information  

### ▶ Order Confirmation
- Verify success message is displayed after placing the order  
- Verify order confirmation page is displayed after successful order placement  

### ▶ Post-Order Actions
- Verify user is able to continue shopping after placing the order  
- Verify user is able to cancel the order before final confirmation (if option available)  
