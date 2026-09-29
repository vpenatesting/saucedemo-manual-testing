# SauceDemo E-commerce — Test Cases

## Login Testing

### TC-001 — Login with Valid Credentials

**Scenario ID:** TS-001
**Priority:** High
**Type:** Functional / Positive

**Preconditions:**

* User is on the SauceDemo login page.
* Valid login credentials are available.

**Test Data:**

* Username: standard_user
* Password: secret_sauce

**Steps:**

1. Enter `standard_user` in the Username field.
2. Enter `secret_sauce` in the Password field.
3. Click the **Login** button.

**Expected Result:**

* User is successfully logged in.
* User is redirected to the Products/Inventory page.

**Actual Result:**
User successfully logged in and was redirected to the Products page.

**Status:** Pass

---

### TC-002 — Login with Invalid Username

**Scenario ID:** TS-002
**Priority:** High
**Type:** Functional / Negative

**Preconditions:**

* User is on the SauceDemo login page.

**Test Data:**

* Username: invalid_user
* Password: secret_sauce

**Steps:**

1. Enter an invalid username.
2. Enter `secret_sauce` in the Password field.
3. Click **Login**.

**Expected Result:**

* Login is unsuccessful.
* An appropriate error message is displayed.
* User remains on the login page.

**Actual Result:**
Login was unsuccessful. An error message was displayed and the user remained on the login page.

**Status:** Pass

---

### TC-003 — Login with Invalid Password

**Scenario ID:** TS-003
**Priority:** High
**Type:** Functional / Negative

**Preconditions:**

* User is on the SauceDemo login page.

**Test Data:**

* Username: standard_user
* Password: invalid_password

**Steps:**

1. Enter `standard_user` in the Username field.
2. Enter an invalid password.
3. Click **Login**.

**Expected Result:**

* Login is unsuccessful.
* An appropriate error message is displayed.
* User remains on the login page.

**Actual Result:**
*To be completed during test execution.*

**Status:** Not Executed

---

### TC-004 — Login with Blank Username

**Scenario ID:** TS-004
**Priority:** High
**Type:** Functional / Negative

**Preconditions:**

* User is on the SauceDemo login page.

**Steps:**

1. Leave the Username field blank.
2. Enter `secret_sauce` in the Password field.
3. Click **Login**.

**Expected Result:**

* Login is unsuccessful.
* A validation/error message is displayed indicating that a username is required.

**Actual Result:**
*To be completed during test execution.*

**Status:** Not Executed

---

## Product Inventory Testing

### TC-005 — Verify Products Are Displayed

**Scenario ID:** TS-007
**Priority:** High
**Type:** Functional / Positive

**Preconditions:**

* User is successfully logged in.

**Steps:**

1. Navigate to the Products page.
2. Review the products displayed.

**Expected Result:**

* Products are displayed.
* Each product contains the expected product information.

**Actual Result:**
*To be completed during test execution.*

**Status:** Not Executed

---

### TC-006 — Verify Product Information

**Scenario ID:** TS-008
**Priority:** Medium
**Type:** Functional

**Preconditions:**

* User is logged in.
* Products page is displayed.

**Steps:**

1. Select a product.
2. Review the product information.

**Expected Result:**

* Product name is displayed.
* Product image is displayed.
* Product price is displayed.
* Product description is displayed where applicable.
* Add-to-cart functionality is available.

**Actual Result:**
*To be completed during test execution.*

**Status:** Not Executed

---

## Product Sorting Testing

### TC-007 — Sort Products A to Z

**Scenario ID:** TS-011
**Priority:** Medium
**Type:** Functional

**Preconditions:**

* User is logged in.
* Products page is displayed.

**Steps:**

1. Open the product sorting dropdown.
2. Select **Name (A to Z)**.
3. Review the product order.

**Expected Result:**

* Products are displayed in alphabetical order from A to Z.

**Actual Result:**
*To be completed during test execution.*

**Status:** Not Executed

---

### TC-008 — Sort Products by Price Low to High

**Scenario ID:** TS-013
**Priority:** Medium
**Type:** Functional

**Preconditions:**

* User is logged in.
* Products page is displayed.

**Steps:**

1. Open the product sorting dropdown.
2. Select **Price (low to high)**.
3. Review the product order.

**Expected Result:**

* Products are displayed from the lowest price to the highest price.

**Actual Result:**
*To be completed during test execution.*

**Status:** Not Executed

---

## Shopping Cart Testing

### TC-009 — Add Product to Cart

**Scenario ID:** TS-015
**Priority:** High
**Type:** Functional / Positive

**Preconditions:**

* User is logged in.
* Products page is displayed.

**Steps:**

1. Select a product.
2. Click **Add to cart**.
3. Open the shopping cart.

**Expected Result:**

* Selected product is added to the cart.
* Product name and price are displayed correctly.
* Cart item count is updated.

**Actual Result:**
*To be completed during test execution.*

**Status:** Not Executed

---

### TC-010 — Remove Product from Cart

**Scenario ID:** TS-018
**Priority:** High
**Type:** Functional / Positive

**Preconditions:**

* User is logged in.
* At least one product has been added to the cart.

**Steps:**

1. Open the shopping cart.
2. Locate the product.
3. Click **Remove**.

**Expected Result:**

* Product is removed from the cart.
* Cart contents are updated.
* Cart item count is updated appropriately.

**Actual Result:**
*To be completed during test execution.*

**Status:** Not Executed
