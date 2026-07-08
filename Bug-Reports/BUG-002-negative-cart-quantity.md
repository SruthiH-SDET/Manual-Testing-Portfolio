# Bug Report: BUG-002

## Summary

The shopping cart accepts a quantity of **0**, allowing users to proceed with an invalid quantity.

---

## Bug ID

BUG-002

## Module

Shopping Cart

## Environment

- Application: E-Commerce Web Application
- Environment: QA
- Browser: Google Chrome (Latest)
- Operating System: Windows 11

---

## Severity

Medium

## Priority

Medium

---

## Preconditions

- User is logged in.
- At least one product has been added to the cart.

---

## Steps to Reproduce

1. Open the Shopping Cart.
2. Edit the product quantity.
3. Enter **0**.
4. Update the cart.

---

## Expected Result

The application should reject quantities less than 1 and display a validation message.

---

## Actual Result

The application accepts a quantity of 0 and updates the cart.

---

## Reproducibility

Always (100%)

---

## Status

Open

---

## Notes

The minimum allowed quantity should be 1.
