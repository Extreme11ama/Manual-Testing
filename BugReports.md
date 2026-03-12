# Bug Reports – Sauce Demo

---

## BUG-001: Checkout allowed with empty cart

**Severity:** High  
**Status:** Open  
**Feature:** Checkout  

**Steps to Reproduce:**
1. Log in with valid credentials
2. Do not add any items to the cart
3. Click the cart icon
4. Click "Checkout"

**Expected Result:**  
Checkout should be disabled or show an error message when cart is empty.

**Actual Result:**  
Checkout proceeds to the customer information form with no items in the cart.

---

## BUG-002: Zip code field accepts non-numeric characters

**Severity:** Medium  
**Status:** Open  
**Feature:** Checkout  

**Steps to Reproduce:**
1. Log in with valid credentials
2. Add any item to the cart
3. Click the cart icon
4. Click "Checkout"
5. Fill in First Name and Last Name
6. Enter letters (e.g. "abcde") in the Zip Code field
7. Click "Continue"

**Expected Result:**  
Zip Code field should only accept numeric characters and enforce a valid length (e.g., 5 digits).

**Actual Result:**  
Checkout proceeds to the overview page with no validation error. The field accepts any input — letters, numbers, or a mix — with no length or format restrictions.