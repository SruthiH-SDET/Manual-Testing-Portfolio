# Registration Test Cases

## Module: User Registration

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result |
|---------------|---------------|------------|-----------|-----------------|
| TC-011 | Register with valid information | Enter all required fields and click Register | New user details | User account is created successfully. |
| TC-012 | Register with an existing email | Enter an email already registered | Existing email | Error message indicates the email is already in use. |
| TC-013 | Verify mandatory fields | Leave required fields blank and click Register | Blank fields | Validation messages are displayed for required fields. |
| TC-014 | Verify password confirmation | Enter different values for Password and Confirm Password | Password mismatch | Error message indicates passwords do not match. |
| TC-015 | Verify invalid email format | Enter an incorrectly formatted email | johnexample.com | Validation message for invalid email format. |
| TC-016 | Verify minimum password length | Enter a password with fewer than 8 characters | Pass1 | Validation message is displayed. |
| TC-017 | Verify maximum password length | Enter a password longer than the allowed limit | 30+ character password | Validation message is displayed. |
| TC-018 | Verify successful registration email | Complete registration successfully | Valid user details | Confirmation email is sent to the registered email address. |
| TC-019 | Verify Terms and Conditions checkbox | Leave Terms and Conditions unchecked | Valid user details | Registration is blocked until the checkbox is selected. |
| TC-020 | Verify successful login after registration | Register a new user and log in | Newly created account | User logs in successfully. |
