## Test Case ID: AUTH-012_user_role_redirection
### Title: Role Redirection - Verify user is redirected to MapScreen after login

**Summary**: Verify that a user with the "user" role is redirected to the MapScreen after successful login.

**Preconditions**: 
- User account exists with "user" role.
- User is on the Sign In screen.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Enter valid user credentials              | Credentials are accepted                               |
| 2 | Tap the "Sign In" button                  | Login process initiates                                |
| 3 | Observe the screen after login            | User is redirected to the MapScreen                    |

**Post-conditions**:
- User is on the MapScreen.
- User has access to user functionalities.
