## Test Case ID: AUTH-007_signin_incorrect_password
### Title: User Sign In - Attempt login with incorrect password

**Summary**: Verify that login fails when an incorrect password is entered.

**Preconditions**: 
- NAVSU app is installed and launched.
- User account exists with known credentials.
- User is on the Sign In screen.
- Internet connection is available.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Enter a valid registered email address    | Email is accepted with no validation errors            |
| 2 | Enter an incorrect password               | Password is accepted                                   |
| 3 | Tap the "Sign In" button                  | Login attempt is processed                             |
| 4 | Observe the response                      | Error message appears indicating incorrect password    |
| 5 | Try again with correct password           | Login succeeds                                         |

**Post-conditions**:
- User is not logged in with incorrect password.
- Account remains secure.
