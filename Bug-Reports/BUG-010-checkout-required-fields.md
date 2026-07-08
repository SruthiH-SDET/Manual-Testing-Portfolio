# Bug Report: BUG-010

## Summary

Checkout is completed even when mandatory shipping fields are blank.

## Module

Checkout

## Severity

Critical

## Priority

Critical

## Steps

1. Add a product to the cart.
2. Proceed to Checkout.
3. Leave Shipping Address blank.
4. Click Place Order.

## Expected Result

Validation messages should appear.

## Actual Result

Order is placed successfully.

## Status

Open
