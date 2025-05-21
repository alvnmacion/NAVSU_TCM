## Test Case ID: AUTH-006_admin_signin_successful
### Title: User Sign In - Successful login with valid credentials (admin role)

**Summary**: Verify that an admin can successfully log in using valid credentials and is redirected to the Admin Screen.

**Preconditions**: 
- NAVSU app is installed and launched.
- Admin account exists with known credentials.
- User is on the Sign In screen.
- Internet connection is available.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Enter a valid admin email address         | Email is accepted with no validation errors            |
| 2 | Enter the correct password                | Password is accepted with no validation errors         |
| 3 | Tap the "Sign In" button                  | Login process initiates                                |
| 4 | Observe the screen after login            | Admin is redirected to the Admin Screen                |

**Post-conditions**:
- Admin session is active.
- Admin has access to admin functionalities.
