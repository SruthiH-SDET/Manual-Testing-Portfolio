# Checkout Test Cases

**Module:** Checkout

**Application:** E-Commerce Web Application

**Version:** 1.0

---

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result |
|---------------|---------------|------------|-----------|-----------------|
| TC-041 | Checkout with valid details | Add products to cart, enter valid shipping details, click Place Order | Valid address and payment information | Order is placed successfully and confirmation page is displayed. |
| TC-042 | Checkout with empty cart | Click Checkout without any products | Empty cart | User is prompted to add products before checkout. |
| TC-043 | Required field validation | Leave mandatory shipping fields blank | Blank fields | Validation messages are displayed. |
| TC-044 | Invalid ZIP/Postal Code | Enter an invalid postal code | 123 | Validation message is displayed. |
| TC-045 | Invalid phone number | Enter letters in the phone number field | ABC123 | Validation message is displayed. |
| TC-046 | Apply a valid discount code | Enter a valid promo code | SAVE10 | Discount is applied successfully. |
| TC-047 | Apply an invalid discount code | Enter an invalid promo code | TEST123 | Error message is displayed. |
| TC-048 | Verify order summary | Review products, quantities, and prices before placing the order | Existing cart | Order summary is accurate. |
| TC-049 | Cancel checkout | Click Cancel during checkout | N/A | User returns to the shopping cart without losing cart contents. |
| TC-050 | Successful order confirmation | Complete checkout successfully | Valid order | Confirmation page displays order number and order details. |
