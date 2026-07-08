# Bug Report: BUG-004

## Summary

The checkout accepts an invalid discount code and applies a discount.

## Bug ID

BUG-004

## Module

Checkout

## Severity

High

## Priority

High

## Steps to Reproduce

1. Add products to the cart.
2. Proceed to Checkout.
3. Enter **SAVE1000**.
4. Apply the code.

## Expected Result

An error message should appear.

## Actual Result

The discount is applied.

## Status

Open
