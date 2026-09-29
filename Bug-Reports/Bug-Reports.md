# SauceDemo Bug Reports

## BUG-001 — Product Images Display Incorrectly

**Bug ID:** BUG-001

**Title:** Product images display the same dog image instead of the corresponding product images

**Environment:**

* Application: SauceDemo
* Browser: Safari
* Operating System: MacOS
* User: `problem_user`

**Severity:** Medium

**Priority:** Medium

**Status:** Open

### Preconditions

* User is on the SauceDemo login page.
* User has valid `problem_user` credentials.

### Steps to Reproduce

1. Log in using the username `problem_user`.
2. Enter the password `secret_sauce`.
3. Click **Login**.
4. Navigate to the Products page.
5. Review the product images displayed.

### Expected Result

Each product should display an image that corresponds to the product being listed.

### Actual Result

All products display the same dog image instead of displaying images corresponding to their individual products.

### Impact

Users may have difficulty identifying products visually and may receive incorrect visual information about the products they are viewing.

### Evidence

Screenshot should be added here if available.

### Notes

The issue was observed while testing the Products page using the `problem_user` account.
