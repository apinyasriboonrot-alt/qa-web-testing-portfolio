# Cart Module – Test Scenarios

## Functional
SC-CART-F-01 Verify user can add product to cart
SC-CART-F-02 Verify user can add multiple different products
SC-CART-F-03 Verify user can increase product quantity
SC-CART-F-04 Verify user can decrease product quantity
SC-CART-F-05 Verify user can remove single product
SC-CART-F-06 Verify cart displays correct product name
SC-CART-F-07 Verify cart displays correct product price
SC-CART-F-08 Verify cart calculates subtotal correctly
SC-CART-F-09 Verify cart updates automatically after quantity change
SC-CART-F-10 Verify cart persists after page refresh
  
## Negative
SC-CART-N-01 Verify system handles adding out-of-stock product
SC-CART-N-02 Verify system prevents negative quantity
SC-CART-N-03 Verify system blocks quantity beyond stock limit
SC-CART-N-04 Verify remove item not existing in cart
SC-CART-N-05 Verify cart behavior when product deleted from system
SC-CART-N-06 Verify adding product without login (if restricted)
SC-CART-N-07 Verify concurrent cart update from multiple tabs
SC-CART-N-08 Verify cart behavior when network disconnects
SC-CART-N-09 Verify rapid multiple add clicks handled correctly
SC-CART-N-10 Verify cart does not duplicate items unexpectedly

## Boundary
SC-CART-B-01 Verify cart with 0 items (empty cart state)
SC-CART-B-02 Verify cart with 1 item
SC-CART-B-03 Verify cart with maximum allowed items
SC-CART-B-04 Verify quantity = 1 (minimum allowed)
SC-CART-B-05 Verify quantity at maximum stock limit
SC-CART-B-06 Verify quantity just above maximum stock limit
SC-CART-B-07 Verify subtotal rounding boundary (decimal cases)
SC-CART-B-08 Verify very high price product in cart
SC-CART-B-09 Verify cart session timeout boundary
SC-CART-B-10 Verify cart persistence across login session boundary

## UI/UX
SC-CART-UI-01 Verify cart layout alignment on desktop
SC-CART-UI-02 Verify cart layout on mobile
SC-CART-UI-03 Verify quantity input field behavior
SC-CART-UI-04 Verify remove button visibility and position
SC-CART-UI-05 Verify subtotal updates visually after change
SC-CART-UI-06 Verify empty cart message display
SC-CART-UI-07 Verify loading indicator during cart update
SC-CART-UI-08 Verify error message display when stock exceeded
SC-CART-UI-09 Verify cart badge count matches cart page
SC-CART-UI-10 Verify accessibility (tab navigation & screen reader support)
