# Demo OpenCart Test Cases

This document contains detailed test cases for demo.opencart.com, covering Login, Registration, Search, Product, Cart, Checkout, Payment, Wishlist, and UI modules.

## Login Module

| TC ID | Test Case Description | Steps | Test Data | Expected Result | Priority |
|-------|--------------------|-------|-----------|----------------|----------|
| TC001 | Verify login with valid credentials | Open website → My Account → Login → Enter valid username & password → Click Login | Valid email & password | User redirected to account dashboard | High |
| TC002 | Verify login with invalid password | Enter valid email & wrong password → Click Login | Valid email / invalid password | Error message displayed | High |
| TC003 | Verify login with invalid email | Enter invalid email & valid password → Click Login | Invalid email / valid password | Error message displayed | High |
| TC004 | Verify login with empty email | Leave email blank → Enter password → Click Login | Password only | Warning message displayed | Medium |
| TC005 | Verify login with empty password | Enter valid email → Leave password blank → Click Login | Email only | Warning message displayed | Medium |
| TC006 | Verify account registration with valid data | My Account → Register → Fill details → Submit | Name, email, password | Account created successfully | High |
| TC007 | Verify account registration with existing email | Register using existing email → Submit | Existing email | Error: Email already registered | High |

## Search Module

| TC ID | Test Case Description | Steps | Test Data | Expected Result | Priority |
|-------|--------------------|-------|-----------|----------------|----------|
| TC008 | Verify search with valid product name | Enter product name in search → Click Search | Product: 'MacBook' | Correct products displayed | High |
| TC009 | Verify search with invalid product name | Enter invalid product name → Click Search | Product: 'XYZ123' | No products found message displayed | Medium |
| TC010 | Verify search with empty input | Leave search empty → Click Search | None | Suggestion or no products displayed | Medium |
| TC011 | Verify category filter | Select category → Apply filter | Category: Desktops → PCs | Only products from selected category displayed | High |
| TC012 | Verify sorting by Price (Low → High) | Sort products by price | N/A | Products sorted ascending | Medium |
| TC013 | Verify sorting by Rating | Sort products by rating | N/A | Products sorted by rating | Medium |

## Product Module

| TC ID | Test Case Description | Steps | Test Data | Expected Result | Priority |
|-------|--------------------|-------|-----------|----------------|----------|
| TC014 | Verify product image opens in zoom | Click on product image | N/A | Image zoom popup opens | Medium |
| TC015 | Verify product description is displayed | Open product page | N/A | Correct product description shown | Medium |
| TC016 | Verify product reviews can be submitted | Scroll to reviews → Submit review | Review text & rating | Review successfully submitted | Medium |
| TC017 | Verify adding product to wishlist | Click 'Add to Wishlist' | Product selected | Success message displayed | Medium |
| TC018 | Verify adding product to comparison | Click 'Compare this Product' | Product selected | Product added to comparison | Medium |
| TC019 | Verify selecting product options | Select options (size/color) → Add to cart | Product options | Selected options applied | Medium |

## Cart Module

| TC ID | Test Case Description | Steps | Test Data | Expected Result | Priority |
|-------|--------------------|-------|-----------|----------------|----------|
| TC020 | Verify adding product to cart | Click 'Add to Cart' | Product selected | Product added successfully | High |
| TC021 | Verify removing product from cart | Remove product from cart | Product in cart | Product removed, cart updated | High |
| TC022 | Verify updating quantity in cart | Change quantity → Update cart | Product & quantity | Quantity updated, subtotal recalculated | High |
| TC023 | Verify checkout with empty cart | Click Checkout with empty cart | None | Warning message displayed | Medium |
| TC024 | Verify applying invalid coupon code | Enter invalid coupon → Apply | Invalid code | Error message displayed | Medium |
| TC025 | Verify applying valid coupon code | Enter valid coupon → Apply | Valid code | Discount applied | Medium |
| TC026 | Verify adding multiple products to cart | Add multiple products → Check cart | Multiple products | All products added correctly | High |

## Checkout Module

| TC ID | Test Case Description | Steps | Test Data | Expected Result | Priority |
|-------|--------------------|-------|-----------|----------------|----------|
| TC027 | Verify checkout as guest | Click Checkout → Guest Checkout | Guest info | Checkout completed successfully | High |
| TC028 | Verify checkout as registered user | Login → Checkout | Account info | Checkout completed successfully | High |
| TC029 | Verify adding new shipping address | Checkout → Add new address | Address details | New address saved and selectable | Medium |
| TC030 | Verify selecting existing shipping address | Checkout → Select address | Existing address | Address selected successfully | Medium |
| TC031 | Verify selecting shipping method | Checkout → Select shipping | Shipping options | Shipping method applied | Medium |
| TC032 | Verify selecting payment method | Checkout → Select payment | Payment options | Payment method applied | Medium |
| TC033 | Verify terms & conditions checkbox validation | Checkout → Submit without checking T&C | N/A | Warning message displayed | Medium |
| TC034 | Verify order confirmation page | Complete checkout | N/A | Order summary displayed | High |
| TC035 | Verify order confirmation email received | Complete checkout | N/A | Confirmation email sent | High |
| TC036 | Verify cancel order option | Cancel order from dashboard | Placed order | Order cancelled successfully | Medium |

## Payment Module

| TC ID | Test Case Description | Steps | Test Data | Expected Result | Priority |
|-------|--------------------|-------|-----------|----------------|----------|
| TC037 | Verify payment with valid credit card | Checkout → Enter valid card | Card details | Payment successful | High |
| TC038 | Verify payment with invalid card number | Checkout → Enter invalid card | Invalid card | Payment failed, error shown | High |
| TC039 | Verify payment without selecting payment | Checkout → Skip payment selection | N/A | Warning message displayed | Medium |
| TC040 | Verify payment with expired card | Checkout → Enter expired card | Expired card | Payment failed | High |
| TC041 | Verify payment with PayPal | Checkout → Select PayPal | PayPal account | Redirect to PayPal, payment completed | High |

## Wishlist/Account Module

| TC ID | Test Case Description | Steps | Test Data | Expected Result | Priority |
|-------|--------------------|-------|-----------|----------------|----------|
| TC042 | Verify adding product to wishlist | Click 'Add to Wishlist' | Product selected | Product added successfully | Medium |
| TC043 | Verify removing product from wishlist | Remove product | Product in wishlist | Product removed successfully | Medium |
| TC044 | Verify editing account details | My Account → Edit info | New name/email | Details updated successfully | Medium |
| TC045 | Verify changing account password | My Account → Change Password | Old & new password | Password updated successfully | Medium |

## UI Module

| TC ID | Test Case Description | Steps | Test Data | Expected Result | Priority |
|-------|--------------------|-------|-----------|----------------|----------|
| TC046 | Verify header menu links | Click all header links | N/A | Correct pages opened | Medium |
| TC047 | Verify footer links | Click all footer links | N/A | Correct pages opened | Medium |
| TC048 | Verify responsiveness on mobile devices | Open website on mobile | N/A | Layout adjusts correctly | High |
| TC049 | Verify page title matches product/category | Open pages | N/A | Page title correct | Medium |
| TC050 | Verify social media links | Click social icons | N/A | Links open respective pages | Medium |

