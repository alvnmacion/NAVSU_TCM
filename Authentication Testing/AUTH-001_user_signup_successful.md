## Test Case ID: AUTH-001_user_signup_successful
### Title: User Sign Up - Successful registration with new valid credentials

**Summary**: Verify that a new user can successfully register using valid email and password.

**Preconditions**: 
- NAVSU app is installed and launched.
- User is on the Sign Up screen.
- The email being used has not been previously registered.
- Internet connection is available.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Tap on "Sign Up" button from login screen | App navigates to registration form                     |
| 2 | Enter a valid email address               | Email is accepted with no validation errors            |
| 3 | Enter a valid password (min 8 chars, contains uppercase, lowercase, number) | Password is accepted with no validation errors |
| 4 | Tap the "Sign Up" or "Register" button    | Registration completes successfully                    |
| 5 | Observe the screen after registration     | User is redirected to Map Screen or verification screen|

**Post-conditions**:
- User account is created in the system.
- User can log in with the new credentials.
- User receives a confirmation message or email (if implemented).
