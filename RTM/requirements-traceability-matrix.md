
# Requirements Traceability Matrix (RTM)

**Project:** E-Commerce Web Application

**Prepared By:** Your Name

**Version:** 1.0

---

## Purpose

The Requirements Traceability Matrix (RTM) ensures that all business requirements are mapped to corresponding test scenarios, test cases, and reported defects. It helps verify complete test coverage and identifies any gaps in testing.

---

## Requirements Traceability Matrix

| Requirement ID | Business Requirement | Test Scenario | Test Case(s) | Bug ID(s) | Status |
|----------------|----------------------|---------------|--------------|-----------|--------|
| BR-001 | User should be able to register a new account | TS-008 | TC-011 – TC-020 | BUG-003 | ✅ Covered |
| BR-002 | User should be able to log in using valid credentials | TS-001 | TC-001 – TC-010 | BUG-001 | ✅ Covered |
| BR-003 | User should receive validation for invalid login attempts | TS-002 – TS-005 | TC-002 – TC-006 | BUG-001 | ✅ Covered |
| BR-004 | User should be able to search for products | TS-012 – TS-015 | TC-021 – TC-030 | BUG-008 | ✅ Covered |
| BR-005 | User should be able to add products to the shopping cart | TS-016 | TC-031 – TC-040 | BUG-002, BUG-009 | ✅ Covered |
| BR-006 | User should be able to update cart quantities | TS-018 | TC-033 – TC-034 | BUG-002 | ✅ Covered |
| BR-007 | User should be able to remove products from the cart | TS-017 | TC-035 – TC-036 | None | ✅ Covered |
| BR-008 | User should be able to complete checkout | TS-020 – TS-022 | TC-041 – TC-050 | BUG-004, BUG-010 | ✅ Covered |
| BR-009 | User should be able to view order history | TS-025 | TC-050 | BUG-005 | ✅ Covered |
| BR-010 | User should be able to update profile information | TS-023 | Profile Update Testing | BUG-006 | ✅ Covered |
| BR-011 | User should be able to reset a forgotten password | Forgot Password Scenario | Password Reset Testing | BUG-007 | ✅ Covered |

---

## Summary

| Metric | Count |
|---------|------:|
| Business Requirements | 11 |
| Test Scenarios | 25 |
| Test Cases | 50 |
| Reported Bugs | 10 |
| Coverage | 100% |

---

## Notes

- Every business requirement has at least one associated test scenario and test case.
- Reported defects are linked to the relevant business requirements.
- The RTM helps ensure that no requirement is missed during testing.
