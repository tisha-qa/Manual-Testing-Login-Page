Checkout Test Cases — SauceDemo

Website: https://www.saucedemo.com/
Testing Type: Manual Testing
Precondition: User is logged in and has access to the SauceDemo Products page.

TC_CHECKOUT_001 — Verify Checkout Information Page

- Test Data: Username: "standard_user", Password: "secret_sauce"
- Steps to Execute:
  1. Open SauceDemo.
  2. Enter valid username and password.
  3. Click Login.
  4. Add a product to the cart.
  5. Open the cart.
  6. Click Checkout.
- Expected Result: Checkout: Your Information page should open with First Name, Last Name and Postal Code fields.
- Actual Result: All three fields were visible.
- Status: Pass

TC_CHECKOUT_002 — Verify Validation with All Fields Empty

- Precondition: Checkout: Your Information page is open.
- Steps to Execute:
  1. Leave First Name empty.
  2. Leave Last Name empty.
  3. Leave Postal Code empty.
  4. Click Continue.
- Expected Result: Validation error should appear and checkout should not proceed.
- Actual Result: Validation error appeared.
- Status: Pass

TC_CHECKOUT_003 — Verify First Name Validation

- Steps to Execute:
  1. Open Checkout: Your Information page.
  2. Leave First Name empty.
  3. Enter "Rathore" in Last Name.
  4. Enter "452001" in Postal Code.
  5. Click Continue.
- Expected Result: First Name validation error should appear.
- Actual Result: Validation error appeared.
- Status: Pass

TC_CHECKOUT_004 — Verify Last Name Validation

- Steps to Execute:
  1. Open Checkout: Your Information page.
  2. Enter "Tisha" in First Name.
  3. Leave Last Name empty.
  4. Enter "452001" in Postal Code.
  5. Click Continue.
- Expected Result: Last Name validation error should appear.
- Actual Result: Validation error appeared.
- Status: Pass

TC_CHECKOUT_005 — Verify Postal Code Validation

- Steps to Execute:
  1. Open Checkout: Your Information page.
  2. Enter "Tisha" in First Name.
  3. Enter "Rathore" in Last Name.
  4. Leave Postal Code empty.
  5. Click Continue.
- Expected Result: Postal Code validation error should appear.
- Actual Result: Validation error appeared.
- Status: Pass

TC_CHECKOUT_006 — Verify Checkout Overview

- Steps to Execute:
  1. Enter valid First Name, Last Name and Postal Code.
  2. Click Continue.
  3. Check the product details on the overview page.
  4. Check the displayed total amount.
- Expected Result: Checkout Overview should open and product details and total should be correct.
- Actual Result: Overview opened; product and total looked correct.
- Status: Pass

TC_CHECKOUT_007 — Verify Order Completion

- Steps to Execute:
  1. Open the Checkout Overview page.
  2. Click Finish.
  3. Verify the confirmation page and message.
- Expected Result: Order confirmation page should display “Thank you for your order!”
- Actual Result: Confirmation page and message appeared.
- Status: Pass

TC_CHECKOUT_008 — Verify Back Home Navigation

- Steps to Execute:
  1. Complete checkout successfully.
  2. Click Back Home on the confirmation page.
  3. Verify the Products page.
- Expected Result: Products page should open and display the products list.
- Actual Result: Products page opened and products were visible.
- Status: Pass


