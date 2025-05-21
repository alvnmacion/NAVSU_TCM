## Test Case ID: AUTH-005_user_signin_successful
### Title: User Sign In - Successful login with valid credentials (user role)

**Summary**: Verify that a user can successfully log in with valid credentials and is redirected to the MapScreen.

**Preconditions**: 
- NAVSU app is installed and launched.
- User account exists with valid credentials.
- Internet connection is available.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Enter valid email and password on login screen | Credentials are accepted, no validation errors    |
| 2 | Tap the "Sign In" button                  | Login is processed, loading indicator appears          |
| 3 | Observe the screen after login            | User is redirected to MapScreen                        |

**Post-conditions**:
- User is logged in and can access the main app features.
