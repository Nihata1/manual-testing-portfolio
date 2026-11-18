# SauceDemo — Test Execution Report

**Scope** — Login, cart, and checkout  
**Method** — Manual functional testing  
**Recorded results** — 7 executed, 6 passed, 1 failed pending review

| Test case | Scenario | Status | Observed result |
|---|---|---|---|
| [TC-LOGIN-001](test-cases/TC-LOGIN-001-valid-login.md) | Valid login | Passed | The inventory page opened and displayed the product list. |
| [TC-LOGIN-002](test-cases/TC-LOGIN-002-invalid-password.md) | Invalid password | Passed | Login was rejected with an invalid credentials message. |
| [TC-LOGIN-003](test-cases/TC-LOGIN-003-empty-username.md) | Empty username | Passed | The login page displayed a required username message. |
| [TC-CART-001](test-cases/TC-CART-001-add-product.md) | Add a product | Passed | The cart badge showed 1 and the selected product had a quantity of 1. |
| [TC-CART-002](test-cases/TC-CART-002-remove-product.md) | Remove the last product | Passed | The cart emptied and the item count badge disappeared. |
| [TC-CHECKOUT-001](test-cases/TC-CHECKOUT-001-complete-order.md) | Complete an order | Passed | The order overview showed the correct product and quantity. The confirmation message appeared after clicking Finish. |
| [TC-CHECKOUT-002](test-cases/CHECKOUT-002-empty-postal-code.md) | Empty postal code | Failed (pending review) | A message indicated that the postal code was required. |

## Result to Review

For TC-CHECKOUT-002, verify whether checkout stayed on the information page after clicking **Continue**. If it did, the warning and the page behavior both match the expected result. Update the test case and this report to **Passed**.
