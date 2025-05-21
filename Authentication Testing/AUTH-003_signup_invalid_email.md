## Test Case ID: AUTH-003_signup_invalid_email
### Title: User Sign Up - Attempt registration with invalid email format

**Summary**: Verify that the system prevents registration with an invalid email format.

**Preconditions**: 
- NAVSU app is installed and launched.
- User is on the Sign Up screen.
- Internet connection is available.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Tap on "Sign Up" button from login screen | App navigates to registration form                     |
| 2 | Enter an invalid email address (e.g., "user@") | Email field shows validation error                |
| 3 | Enter a valid password                    | Password field accepts the input                       |
| 4 | Tap the "Sign Up" or "Register" button    | Registration is blocked, error message shown           |

**Post-conditions**:
- No account is created.
- User is informed about the invalid email format.
