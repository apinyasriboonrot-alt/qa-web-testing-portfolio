# Checkout Module – Test Scenarios

## Functional
SC-CHECKOUT-F-01 Verify user can navigate from cart to checkout page
SC-CHECKOUT-F-02 Verify user can enter valid shipping information
SC-CHECKOUT-F-03 Verify user can proceed to order summary
SC-CHECKOUT-F-04 Verify order summary displays correct products
SC-CHECKOUT-F-05 Verify subtotal calculation is correct
SC-CHECKOUT-F-06 Verify tax calculation is correct
SC-CHECKOUT-F-07 Verify total amount calculation is correct
SC-CHECKOUT-F-08 Verify user can confirm and complete order
SC-CHECKOUT-F-09 Verify order confirmation message displayed
SC-CHECKOUT-F-10 Verify order ID generated after successful checkout
  
## Negative
SC-CHECKOUT-N-01 Verify checkout fails with empty required fields
SC-CHECKOUT-N-02 Verify invalid postal code rejected
SC-CHECKOUT-N-03 Verify invalid characters in name field rejected
SC-CHECKOUT-N-04 Verify checkout blocked if cart is empty
SC-CHECKOUT-N-05 Verify checkout fails if product becomes out-of-stock
SC-CHECKOUT-N-06 Verify duplicate order prevention on rapid click
SC-CHECKOUT-N-07 Verify session expiration during checkout
SC-CHECKOUT-N-08 Verify manipulated total price via browser dev tools rejected
SC-CHECKOUT-N-09 Verify network interruption during checkout
SC-CHECKOUT-N-10 Verify unauthorized direct access to checkout URL

## Boundary
SC-CHECKOUT-B-01 Verify first name minimum length
SC-CHECKOUT-B-02 Verify first name maximum length
SC-CHECKOUT-B-03 Verify postal code minimum length
SC-CHECKOUT-B-04 Verify postal code maximum length
SC-CHECKOUT-B-05 Verify extremely long address input
SC-CHECKOUT-B-06 Verify total price rounding boundary
SC-CHECKOUT-B-07 Verify checkout with maximum cart items
SC-CHECKOUT-B-08 Verify tax calculation with boundary decimal values
SC-CHECKOUT-B-09 Verify session timeout boundary at confirmation step
SC-CHECKOUT-B-10 Verify order total at maximum system-supported value

## UI/UX
SC-CHECKOUT-UI-01 Verify checkout page layout alignment (desktop)
SC-CHECKOUT-UI-02 Verify checkout page layout alignment (mobile)
SC-CHECKOUT-UI-03 Verify required field indicator displayed correctly
SC-CHECKOUT-UI-04 Verify validation message displayed clearly
SC-CHECKOUT-UI-05 Verify error message disappears after correction
SC-CHECKOUT-UI-06 Verify loading indicator during order submission
SC-CHECKOUT-UI-07 Verify confirm button disabled until form valid
SC-CHECKOUT-UI-08 Verify order summary visually clear and readable
SC-CHECKOUT-UI-09 Verify back button navigation behavior
SC-CHECKOUT-UI-10 Verify accessibility (tab order & screen reader labels)
