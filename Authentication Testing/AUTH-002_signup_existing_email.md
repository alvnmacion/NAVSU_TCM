## Test Case ID: AUTH-002_signup_existing_email
### Title: User Sign Up - Attempt registration with existing email

**Summary**: Verify that the system prevents registration with an email address that is already in use.

**Preconditions**: 
- NAVSU app is installed and launched.
- User is on the Sign Up screen.
- An account with the email already exists.
- Internet connection is available.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Tap on "Sign Up" button from login screen | App navigates to registration form                     |
| 2 | Enter an email address that is already registered | Email field accepts the input                  |
| 3 | Enter a valid password                    | Password field accepts the input                       |
| 4 | Tap the "Sign Up" or "Register" button    | System attempts to process the registration            |
| 5 | Observe the response                      | Error message appears indicating the email is already in use |
| 6 | Verify the form state                     | Registration is not completed and user remains on the Sign Up screen |

**Post-conditions**:
- No new account is created.
- The existing account remains unchanged.
- User is informed about the duplicate email issue.
