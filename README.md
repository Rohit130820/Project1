# E-Commerce Website - Manual and Cypress Testing

This project focuses on both **manual testing** and **automated testing** using **Cypress** for the **E-Commerce Website**. It outlines how to create detailed **test cases**, **test scenarios**, **mind maps**, and **bug reports**, as well as using **Cypress** for end-to-end testing automation.

## Features to Test

- **Product Listings**: Verify that the products are displayed with the correct details (price, description, images).
- **Search Functionality**: Ensure that the search bar and filters work as expected to display relevant products.
- **User Registration & Login**: Test the user registration, login, and authentication system.
- **Shopping Cart**: Verify that users can add, update, and remove items from the shopping cart.
- **Checkout Process**: Ensure the checkout process is smooth and correct, including payment and order confirmation.
- **Payment Gateway**: Test the functionality of the payment gateway integration.
- **Responsive Design**: Ensure the website is responsive across various devices.
- **Error Handling**: Verify that the application shows appropriate error messages for invalid actions (e.g., invalid email, payment errors).



### 2. Test Scenarios

Test scenarios define high-level testing goals and approaches. Below are some test scenarios for the **E-Commerce Website**:

- **Test Scenario 1**: **User Registration and Login**
  - **Objective**: Ensure users can register, log in, and reset passwords.
  - **Test Steps**: Register with valid details, log in with correct credentials, and test password recovery with an invalid email.
  - **Expected Result**: User should be able to register, log in, and reset their password with the correct error message if credentials are incorrect.

- **Test Scenario 2**: **Product Listing and Search**
  - **Objective**: Ensure that products display correctly and search functionality works as expected.
  - **Test Steps**: Navigate through product categories, use the search bar with different keywords, and verify results.
  - **Expected Result**: The website should show the correct products in each category and search results should match the query.

- **Test Scenario 3**: **Shopping Cart and Checkout**
  - **Objective**: Test adding products to the shopping cart, proceeding to checkout, and completing the payment.
  - **Test Steps**: Add multiple products to the cart, proceed to checkout, enter payment details, and confirm the purchase.
  - **Expected Result**: Products should be added to the cart, and the checkout process should complete with an order confirmation.

- **Test Scenario 4**: **Payment Gateway Integration**
  - **Objective**: Ensure the payment gateway functions correctly.
  - **Test Steps**: Go to the checkout page, enter valid payment details, and complete the purchase.
  - **Expected Result**: The transaction should be successful, and a confirmation page should appear.

### 3. Mind Map for Manual Testing

A **Mind Map** helps visually organize your manual testing approach. Here's an example structure for the **E-Commerce Website** testing:

