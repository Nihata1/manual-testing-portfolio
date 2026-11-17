# TC-LOGIN-003 — Login with an Empty Username

## Preconditions

- The user is signed out.
- The [SauceDemo login page](https://www.saucedemo.com/) is open.

## Test Data

| Field | Value |
|---|---|
| Username | Leave blank |
| Password | `secret_sauce` |

## Test Steps

1. Leave the **Username** field blank.
2. Enter the password from the test data.
3. Click **Login**.

## Expected Result

The login page stays open and displays a validation message indicating that the username is required.

## Execution

- **Status** — Not Run
- **Actual result** — Pending execution
