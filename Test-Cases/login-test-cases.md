# Login Test Cases

## Module: User Login

| Test Case ID | Test Scenario | Test Steps | Test Data | Expected Result |
|---------------|---------------|------------|-----------|-----------------|
| TC-001 | Login with valid credentials | 1. Open Login page<br>2. Enter valid email<br>3. Enter valid password<br>4. Click Login | Email: qauser@test.com<br>Password: Password123 | User is successfully logged in and redirected to the dashboard. |
| TC-002 | Login with invalid password | Enter valid email and incorrect password | Password: WrongPass123 | Error message is displayed and login is denied. |
| TC-003 | Login with invalid email | Enter invalid email and valid password | Email: invalid@test.com | Error message is displayed. |
| TC-004 | Login with blank email | Leave email field empty | Blank email | Validation message appears requesting email. |
| TC-005 | Login with blank password | Leave password field empty | Blank password | Validation message appears requesting password. |
| TC-006 | Login with both fields blank | Click Login without entering credentials | None | Required field validation messages appear. |
| TC-007 | Verify password masking | Type password in password field | Password123 | Password characters are hidden. |
| TC-008 | Verify Remember Me | Select Remember Me and login | Valid credentials | User remains logged in after browser restart. |
| TC-009 | Verify Logout | Login successfully and click Logout | Valid credentials | User is logged out and redirected to Login page. |
| TC-010 | Verify SQL Injection prevention | Enter `' OR '1'='1` in email/password fields | SQL Injection string | Login fails and application remains secure. |
