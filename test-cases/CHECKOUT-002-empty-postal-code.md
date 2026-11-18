# TC-CHECKOUT-002 — Checkout with an Empty Postal Code

## Preconditions

- The user is signed in to SauceDemo as `standard_user`.
- The Your Cart page is open and contains one Sauce Labs Bolt T-Shirt.

## Test Data

| Field | Value |
|---|---|
| First Name | Alex |
| Last Name | Tester |
| Zip/Postal Code | Leave blank |

## Test Steps

1. Click **Checkout**.
2. Enter the first and last names from the test data.
3. Leave **Zip/Postal Code** blank.
4. Click **Continue**.

## Expected Result

Checkout blocks progression to the order overview and displays a validation message indicating that the postal code is required.

## Execution

- **Status** — Failed
- **Actual result** — checkout failed a error message indicating that Postal Code is required

