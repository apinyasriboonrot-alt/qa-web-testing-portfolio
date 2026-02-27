# Product Module – Test Scenarios

## Functional
SC-PRODUCT-F-01 Verify product list displays after login
SC-PRODUCT-F-02 Verify product name, price, and image display correctly
SC-PRODUCT-F-03 Verify user can open product detail page
SC-PRODUCT-F-04 Verify add to cart from product list
SC-PRODUCT-F-05 Verify add to cart from product detail page
SC-PRODUCT-F-06 Verify remove from cart from product list
SC-PRODUCT-F-07 Verify cart badge updates after adding item
SC-PRODUCT-F-08 Verify sorting by name (A–Z)
SC-PRODUCT-F-09 Verify sorting by price (low to high)
SC-PRODUCT-F-10 Verify product detail information matches listing page

## Negative
SC-PRODUCT-N-01 Verify behavior when product image fails to load
SC-PRODUCT-N-02 Verify behavior when product price is missing
SC-PRODUCT-N-03 Verify system behavior when product name is null
SC-PRODUCT-N-04 Verify add to cart without login (direct URL access)
SC-PRODUCT-N-05 Verify rapid multiple clicks on add to cart
SC-PRODUCT-N-06 Verify remove item not present in cart
SC-PRODUCT-N-07 Verify invalid sorting option manipulation via URL
SC-PRODUCT-N-08 Verify product detail page access with invalid product ID
SC-PRODUCT-N-09 Verify product page refresh during cart update
SC-PRODUCT-N-10 Verify multi-tab cart update conflict

## Boundary  
SC-PRODUCT-B-01 Verify behavior when product list has 0 items
SC-PRODUCT-B-02 Verify behavior when product list has 1 item
SC-PRODUCT-B-03 Verify behavior when product list has large volume (1000+ items)
SC-PRODUCT-B-04 Verify product name minimum character length
SC-PRODUCT-B-05 Verify product name maximum character length
SC-PRODUCT-B-06 Verify product price equals 0
SC-PRODUCT-B-07 Verify product price with large numeric value
SC-PRODUCT-B-08 Verify product price with multiple decimal places
SC-PRODUCT-B-09 Verify maximum number of items added to cart
SC-PRODUCT-B-10 Verify pagination boundary (first page / last page)

## UI/UX
SC-PRODUCT-UI-01 Verify layout alignment on desktop view
SC-PRODUCT-UI-02 Verify layout alignment on mobile view
SC-PRODUCT-UI-03 Verify product image resolution and scaling
SC-PRODUCT-UI-04 Verify hover effect on product card
SC-PRODUCT-UI-05 Verify add to cart button state change after click
SC-PRODUCT-UI-06 Verify sorting dropdown UI behavior
SC-PRODUCT-UI-07 Verify loading indicator while product loads
SC-PRODUCT-UI-08 Verify consistent font and color style
SC-PRODUCT-UI-09 Verify cart badge position and visibility
SC-PRODUCT-UI-10 Verify accessibility (tab navigation / keyboard selection)
