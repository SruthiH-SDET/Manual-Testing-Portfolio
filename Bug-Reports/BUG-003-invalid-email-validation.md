# Bug Report: BUG-003

## Summary

The Registration page accepts an invalid email address without displaying a validation message.

---

## Bug ID

BUG-003

## Module

User Registration

## Environment

- Application: E-Commerce Web Application
- Environment: QA
- Browser: Google Chrome (Latest)
- Operating System: Windows 11

---

## Severity

Medium

## Priority

High

---

## Preconditions

- User is on the Registration page.

---

## Steps to Reproduce

1. Open the Registration page.
2. Enter all required information.
3. Enter **johnexample.com** as the email address.
4. Click **Register**.

---

## Expected Result

The application should reject the invalid email format and display a validation message.

---

## Actual Result

The application accepts the invalid email address and creates the account.

---

## Reproducibility

Always (100%)

---

## Status

Open

---

## Suggested Fix

Validate the email format before submitting the registration form.
