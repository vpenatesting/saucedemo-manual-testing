# SauceDemo E-commerce — Test Scenarios

## 1. Login

| Scenario ID | Test Scenario                                 |
| ----------- | --------------------------------------------- |
| TS-001      | Verify user can log in with valid credentials |
| TS-002      | Verify login fails with an invalid username   |
| TS-003      | Verify login fails with an invalid password   |
| TS-004      | Verify login fails when username is blank     |
| TS-005      | Verify login fails when password is blank     |
| TS-006      | Verify user can log out successfully          |

## 2. Product Inventory

| Scenario ID | Test Scenario                                                        |
| ----------- | -------------------------------------------------------------------- |
| TS-007      | Verify products are displayed on the inventory page                  |
| TS-008      | Verify each product displays a name, image, price, and action button |
| TS-009      | Verify user can open a product's details                             |
| TS-010      | Verify user can return from product details to the inventory page    |

## 3. Product Sorting

| Scenario ID | Test Scenario                                           |
| ----------- | ------------------------------------------------------- |
| TS-011      | Verify products can be sorted by name from A to Z       |
| TS-012      | Verify products can be sorted by name from Z to A       |
| TS-013      | Verify products can be sorted by price from low to high |
| TS-014      | Verify products can be sorted by price from high to low |

## 4. Shopping Cart

| Scenario ID | Test Scenario                                           |
| ----------- | ------------------------------------------------------- |
| TS-015      | Verify user can add a product to the shopping cart      |
| TS-016      | Verify the cart displays the correct product            |
| TS-017      | Verify the cart displays the correct product price      |
| TS-018      | Verify user can remove a product from the cart          |
| TS-019      | Verify the cart count updates when products are added   |
| TS-020      | Verify the cart count updates when products are removed |

## 5. Checkout

| Scenario ID | Test Scenario                                                     |
| ----------- | ----------------------------------------------------------------- |
| TS-021      | Verify user can proceed from the cart to checkout                 |
| TS-022      | Verify checkout requires a first name                             |
| TS-023      | Verify checkout requires a last name                              |
| TS-024      | Verify checkout requires a postal code                            |
| TS-025      | Verify user can continue checkout with valid customer information |
| TS-026      | Verify checkout displays the correct product information          |
| TS-027      | Verify checkout displays the correct subtotal                     |
| TS-028      | Verify checkout displays applicable tax                           |
| TS-029      | Verify checkout displays the correct total                        |
| TS-030      | Verify user can complete an order                                 |

## 6. Order Completion

| Scenario ID | Test Scenario                                                         |
| ----------- | --------------------------------------------------------------------- |
| TS-031      | Verify successful order displays an order confirmation                |
| TS-032      | Verify user can return to the products page after completing an order |

## 7. Negative & Exploratory Testing

| Scenario ID | Test Scenario                                                            |
| ----------- | ------------------------------------------------------------------------ |
| TS-033      | Verify application behavior when invalid information is entered          |
| TS-034      | Verify application behavior when required checkout fields are left blank |
| TS-035      | Verify user cannot continue checkout without required information        |
| TS-036      | Verify cart behavior when products are added and removed repeatedly      |
