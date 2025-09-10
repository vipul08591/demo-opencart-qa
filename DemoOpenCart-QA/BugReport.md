# Bug Reports – Demo OpenCart eCommerce

**Project:** Demo OpenCart eCommerce  
**Reported by:** Vipul  
**Date:** 2025-09-10  

---

## 1. Product Image Not Loading

- **Description:** Some product images fail to load on product listing pages.  
- **Steps to Reproduce:**
  1. Navigate to the Demo OpenCart site.  
  2. Go to "Electronics" category.  
  3. Observe the missing images on some products.  
- **Expected Result:** All product images display correctly.  
- **Actual Result:** Placeholder image appears instead of product image.  
- **Severity:** Medium  

---

## 2. Add to Cart Button Not Working

- **Description:** "Add to Cart" button does not respond for certain products.  
- **Steps to Reproduce:**
  1. Go to "Laptops" category.  
  2. Click "Add to Cart" for "Laptop Model X".  
- **Expected Result:** Product should be added to the cart.  
- **Actual Result:** No action occurs; cart count remains unchanged.  
- **Severity:** High  

---

## 3. Checkout Page Error

- **Description:** Error occurs when proceeding to checkout.  
- **Steps to Reproduce:**
  1. Add any product to the cart.  
  2. Click "Checkout".  
- **Expected Result:** Checkout page loads successfully.  
- **Actual Result:** Error: "Undefined variable: shipping_address".  
- **Severity:** Critical  

---

## 4. Search Function Returns Irrelevant Results

- **Description:** Searching for specific products shows unrelated items.  
- **Steps to Reproduce:**
  1. Enter "iPhone 15" in search bar.  
  2. Click the search button.  
- **Expected Result:** Only iPhone 15 products should appear.  
- **Actual Result:** Other electronics appear in search results.  
- **Severity:** Medium  

---

## 5. Pagination Broken on Category Pages

- **Description:** Clicking "Next" does not load the next set of products.  
- **Steps to Reproduce:**
  1. Go to "Books" category.  
  2. Click "Next" pagination button.  
- **Expected Result:** Next products should load.  
- **Actual Result:** Same products reload.  
- **Severity:** Low  

---

## 6. Login Page Validation Issue

- **Description:** Users can submit login form with empty fields.  
- **Steps to Reproduce:**
  1. Go to "Login" page.  
  2. Leave email and password empty.  
  3. Click "Login".  
- **Expected Result:** Form should show validation error.  
- **Actual Result:** Form submits, redirects with generic error.  
- **Severity:** Medium  

---

## 7. Newsletter Subscription Email Not Sent

- **Description:** Subscribed emails do not receive confirmation.  
- **Steps to Reproduce:**
  1. Enter a valid email in newsletter field.  
  2. Click "Subscribe".  
- **Expected Result:** Confirmation email sent.  
- **Actual Result:** No email received.  
- **Severity:** Medium  

---

## 8. Admin Panel Product Save Error

- **Description:** Admin cannot save new product with image.  
- **Steps to Reproduce:**
  1. Log in to Admin panel.  
  2. Go to "Catalog → Products → Add New".  
  3. Upload an image and save.  
- **Expected Result:** Product saved successfully.  
- **Actual Result:** Error: "Could not upload image".  
- **Severity:** High  

---

## 9. Currency Switcher Not Updating Prices

- **Description:** Changing currency does not update product prices.  
- **Steps to Reproduce:**
  1. Select "EUR" from currency dropdown.  
  2. Observe product prices.  
- **Expected Result:** Prices should update to selected currency.  
- **Actual Result:** Prices remain in default currency.  
- **Severity:** Low  

---

## 10. Mobile Layout Broken

- **Description:** Some pages are not responsive on mobile devices.  
- **Steps to Reproduce:**
  1. Open site on mobile device or use responsive mode.  
  2. Navigate to "Checkout" page.  
- **Expected Result:** Page elements adapt to screen size.  
- **Actual Result:** Layout breaks; buttons overlap text.  
- **Severity:** Medium  

---

## 11. Product Reviews Not Displayed

- **Description:** Reviews added by users are not visible.  
- **Steps to Reproduce:**
  1. Go to a product page.  
  2. Add a review.  
  3. Reload the page.  
- **Expected Result:** Review appears immediately.  
- **Actual Result:** Review does not appear until admin approval (not mentioned).  
- **Severity:** Low  

---


