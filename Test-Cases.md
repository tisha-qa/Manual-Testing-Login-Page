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

Cart Test Cases — SauceDemo

Website: https://www.saucedemo.com/

Precondition: User is logged in and is on the Products page.

TC_CART_001 — Add One Product to Cart

- Steps to Execute:
  1. Open the Products page.
  2. Click Add to cart for one product.
  3. Observe the button and cart badge.
  4. Open the cart.
- Expected Result: Product should appear in the cart and the cart badge should show 1.
- Actual Result: Product appeared in the cart, button changed to Remove, and cart badge showed 1.
- Status: Pass

TC_CART_002 — Remove Product from Cart

- Steps to Execute:
  1. Add one product to the cart.
  2. Open the cart.
  3. Click Remove for that product.
  4. Check the cart contents and badge.
- Expected Result: Product should be removed from the cart.
- Actual Result: Product was removed and the cart became empty.
- Status: Pass

TC_CART_003 — Add Two Different Products

- Steps to Execute:
  1. Open the Products page.
  2. Add the first product to the cart.
  3. Add a second, different product.
  4. Open the cart.
- Expected Result: Both products should appear and the cart badge should show 2.
- Actual Result: Cart badge showed 2 and both products were displayed.
- Status: Pass

TC_CART_004 — Remove One of Two Products

- Steps to Execute:
  1. Add two different products to the cart.
  2. Open the cart.
  3. Remove one product.
  4. Check the remaining product and cart badge.
- Expected Result: One product should remain and the badge should show 1.
- Actual Result: One product remained and the cart badge showed 1.
- Status: Pass

TC_CART_005 — Verify Cart Contents After Adding Products

- Steps to Execute:
  1. Open the Products page.
  2. Add two different products.
  3. Check the cart badge.
  4. Open the cart and inspect the listed products.
- Expected Result: Cart should contain the two selected products, with badge count 2.
- Actual Result: Two different products were displayed in the cart and the badge showed 2.
- Status: Pass

TC_CART_006 — Verify Button After Removing Product

- Steps to Execute:
  1. Add a product to the cart.
  2. Open the cart.
  3. Remove the product.
  4. Return to the Products page.
  5. Check the button for the removed product.
- Expected Result: The product button should change back to Add to cart.
- Actual Result: The button displayed Add to cart again.
- Status: Pass
