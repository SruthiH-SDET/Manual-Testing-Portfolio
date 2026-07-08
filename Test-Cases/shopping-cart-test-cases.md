# Shopping Cart Test Cases

## Module: Shopping Cart

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result |
|---------------|---------------|------------|-----------|-----------------|
| TC-031 | Add a product to the cart | Open a product page and click **Add to Cart** | Laptop | Product is added to the shopping cart successfully. |
| TC-032 | Add multiple products | Add two or more different products | Laptop, Mouse | All selected products appear in the cart. |
| TC-033 | Increase product quantity | Change quantity from 1 to 2 | Quantity = 2 | Cart updates the quantity and total price correctly. |
| TC-034 | Decrease product quantity | Reduce quantity from 2 to 1 | Quantity = 1 | Quantity and total price are updated correctly. |
| TC-035 | Remove a product | Click the Remove button | Existing cart item | Product is removed from the cart. |
| TC-036 | Empty the shopping cart | Remove all items | Multiple products | Shopping cart becomes empty. |
| TC-037 | Verify total price calculation | Add multiple products with different prices | Various products | Total price equals the sum of all items. |
| TC-038 | Continue shopping | Click **Continue Shopping** | N/A | User is redirected to the product listing page. |
| TC-039 | Verify cart persistence | Add products, log out, and log back in | Existing user | Cart contents are retained after login. |
| TC-040 | Attempt checkout with empty cart | Click Checkout without any items | Empty cart | User receives an appropriate message and checkout is blocked. |
