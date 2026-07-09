# Defect Summary Report

**Project:** E-Commerce Web Application

**Prepared By:** Your Name

**Version:** 1.0

**Test Cycle:** Release 1.0

**Date:** July 2026

---

# Objective

The purpose of this report is to summarize all defects identified during the testing cycle and provide an overview of defect severity, priority, and current status.

---

# Defect Metrics

| Metric | Count |
|---------|------:|
| Total Defects Reported | 10 |
| Critical | 1 |
| High | 3 |
| Medium | 4 |
| Low | 2 |
| Open | 10 |
| Closed | 0 |

---

# Defect Summary

| Bug ID | Module | Summary | Severity | Priority | Status |
|--------|--------|---------|----------|----------|--------|
| BUG-001 | Login | Login button does not respond | High | High | Open |
| BUG-002 | Shopping Cart | Quantity accepts invalid value | Medium | Medium | Open |
| BUG-003 | Registration | Invalid email format accepted | Medium | High | Open |
| BUG-004 | Checkout | Invalid discount code accepted | High | High | Open |
| BUG-005 | Order History | Completed orders not displayed | Medium | Medium | Open |
| BUG-006 | User Profile | Profile changes cannot be saved | Medium | High | Open |
| BUG-007 | Forgot Password | Password reset link expires immediately | High | High | Open |
| BUG-008 | Product Search | Price sorting produces incorrect results | Low | Medium | Open |
| BUG-009 | Shopping Cart | Cart is cleared after browser refresh | Low | Medium | Open |
| BUG-010 | Checkout | Order placed with mandatory fields blank | Critical | Critical | Open |

---

# Defects by Module

| Module | Number of Defects |
|--------|------------------:|
| Login | 1 |
| Registration | 1 |
| Shopping Cart | 2 |
| Checkout | 2 |
| Product Search | 1 |
| User Profile | 1 |
| Order History | 1 |
| Forgot Password | 1 |

---

# Severity Distribution

| Severity | Description |
|----------|-------------|
| Critical | Prevents core business functionality. Immediate fix required. |
| High | Major functionality affected with no acceptable workaround. |
| Medium | Functionality affected but a workaround exists. |
| Low | Minor UI or usability issue with minimal business impact. |

---

# Recommendations

- Resolve all Critical and High severity defects before production release.
- Perform full regression testing after defect fixes.
- Retest all resolved defects before closing the test cycle.

---

# Conclusion

A total of **10 defects** were identified during testing. Most defects are related to input validation, shopping cart functionality, and checkout processing. The application should not be released until all Critical and High severity defects have been resolved and successfully retested.
