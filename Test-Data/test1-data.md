# Test Data

**Project:** E-Commerce Web Application

**Prepared By:** Your Name

**Version:** 1.0

---

# Purpose

This document contains sample test data used to validate various modules of the E-Commerce Web Application.

---

# Login Test Data

## Valid Users

| Test ID | Email | Password | Expected Result |
|----------|-------|----------|-----------------|
| TD-001 | qauser@test.com | Password123 | Login Successful |
| TD-002 | admin@test.com | Admin@123 | Login Successful |

---

## Invalid Login Data

| Test ID | Email | Password | Expected Result |
|----------|-------|----------|-----------------|
| TD-003 | qauser@test.com | WrongPassword | Invalid Credentials |
| TD-004 | wrong@test.com | Password123 | Invalid Credentials |
| TD-005 | | Password123 | Email Required |
| TD-006 | qauser@test.com | | Password Required |
| TD-007 | | | Required Field Validation |

---

# Registration Test Data

| Test ID | First Name | Last Name | Email | Password | Expected Result |
|----------|------------|-----------|-------|----------|-----------------|
| TD-008 | John | Smith | john@test.com | Password123 | Registration Successful |
| TD-009 | Sarah | Brown | sarah@test.com | Test@1234 | Registration Successful |
| TD-010 | David | Wilson | david@test.com | Password@1 | Registration Successful |

---

## Invalid Registration Data

| Test ID | Test Data | Expected Result |
|----------|-----------|-----------------|
| TD-011 | Existing Email | Registration Failed |
| TD-012 | Invalid Email Format | Validation Message |
| TD-013 | Password Less Than 8 Characters | Validation Message |
| TD-014 | Passwords Do Not Match | Validation Message |
| TD-015 | Required Fields Blank | Validation Message |

---

# Product Search Test Data

| Test ID | Search Keyword | Expected Result |
|----------|----------------|-----------------|
| TD-016 | Laptop | Products Found |
| TD-017 | Mouse | Products Found |
| TD-018 | Samsung | Products Found |
| TD-019 | ABCXYZ | No Products Found |
| TD-020 | @#$% | Validation / No Results |

---

# Shopping Cart Test Data

| Test ID | Quantity | Expected Result |
|----------|----------|-----------------|
| TD-021 | 1 | Product Added |
| TD-022 | 5 | Quantity Updated |
| TD-023 | 99 | Maximum Quantity Accepted |
| TD-024 | 0 | Validation Message |
| TD-025 | -1 | Validation Message |

---

# Checkout Test Data

## Shipping Address

| Test ID | Name | Address | City | ZIP Code | Expected Result |
|----------|------|---------|------|-----------|-----------------|
| TD-026 | John Smith | 123 Main Street | New York | 10001 | Order Successful |
| TD-027 | Sarah Brown | 456 Oak Avenue | Chicago | 60601 | Order Successful |

---

## Discount Codes

| Test ID | Code | Expected Result |
|----------|------|-----------------|
| TD-028 | SAVE10 | 10% Discount Applied |
| TD-029 | WELCOME20 | 20% Discount Applied |
| TD-030 | INVALID | Invalid Coupon Message |

---

# Boundary Value Test Data

## Password Length

| Test ID | Password Length | Expected Result |
|----------|-----------------|-----------------|
| TD-031 | 7 Characters | Validation Error |
| TD-032 | 8 Characters | Accepted |
| TD-033 | 20 Characters | Accepted |
| TD-034 | 21 Characters | Validation Error |

---

## Product Quantity

| Test ID | Quantity | Expected Result |
|----------|----------|-----------------|
| TD-035 | 0 | Rejected |
| TD-036 | 1 | Accepted |
| TD-037 | 99 | Accepted |
| TD-038 | 100 | Rejected |

---

# Notes

- Test data contains both positive and negative scenarios.
- Boundary Value Analysis (BVA) and Equivalence Partitioning (EP) techniques were used where applicable.
- No real customer information is included.
