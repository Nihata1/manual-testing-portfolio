# TC-CART-002 — Remove the Last Product from the Cart

## Preconditions

- The user is signed in to SauceDemo as `standard_user`.
- The Your Cart page is open.
- The cart contains one unit of **Sauce Labs Bolt T-Shirt** as its only item.

## Test Steps

1. Click **Remove** next to **Sauce Labs Bolt T-Shirt**.
2. Check the cart contents and the item count badge on the cart icon.

## Expected Result

- The cart is empty.
- The item count badge disappears from the cart icon.

## Execution

- **Status** — Passed
- **Actual result** — The cart was empty, and the item count badge disappeared after the last product was removed.
