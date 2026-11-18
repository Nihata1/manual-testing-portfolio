# TC-CHECKOUT-001 — Complete an Order with Valid Details

## Preconditions

- The user is signed in to SauceDemo as `standard_user`.
- The Your Cart page is open and contains one Sauce Labs Bolt T-Shirt.

## Test Data

| Field | Value |
|---|---|
| First Name | Alex |
| Last Name | Tester |
| Zip/Postal Code | `10001` |

## Test Steps

1. Click **Checkout**.
2. Enter the details from the test data.
3. Click **Continue** and review the product and quantity on the order overview.
4. Click **Finish**.

## Expected Result

- The order overview lists **Sauce Labs Bolt T-Shirt** with a quantity of `1`.
- The checkout confirmation page displays **Thank you for your order!**

## Execution

- **Status** — Passed
- **Actual result** — The order overview listed one Sauce Labs Bolt T-Shirt. After clicking Finish, the confirmation page displayed “Thank you for your order!”
