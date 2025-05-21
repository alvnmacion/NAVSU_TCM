## Test Case ID: AUTH-004_signup_weak_password
### Title: User Sign Up - Attempt registration with weak password

**Summary**: Verify that the system prevents registration with a weak password.

**Preconditions**: 
- NAVSU app is installed and launched.
- User is on the Sign Up screen.
- Internet connection is available.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Tap on "Sign Up" button from login screen | App navigates to registration form                     |
| 2 | Enter a valid email address               | Email field accepts the input                          |
| 3 | Enter a weak password (e.g., "12345")     | Password field shows validation error                  |
| 4 | Tap the "Sign Up" or "Register" button    | Registration is blocked, error message shown           |

**Post-conditions**:
- No account is created.
- User is informed about password requirements.
