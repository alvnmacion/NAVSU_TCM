## Test Case ID: AUTH-008_signin_nonexistent_email
### Title: User Sign In - Attempt login with non-existent email

**Summary**: Verify that login fails when a non-existent email is used.

**Preconditions**: 
- NAVSU app is installed and launched.
- User is on the Sign In screen.
- Internet connection is available.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Enter an email address not registered     | Email is accepted                                      |
| 2 | Enter any password                        | Password is accepted                                   |
| 3 | Tap the "Sign In" button                  | Login attempt is processed                             |
| 4 | Observe the response                      | Error message appears indicating account not found     |

**Post-conditions**:
- No session is created.
- User is informed that the account does not exist.
