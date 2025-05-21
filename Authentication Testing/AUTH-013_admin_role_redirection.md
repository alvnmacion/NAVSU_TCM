## Test Case ID: AUTH-013_admin_role_redirection
### Title: Role Redirection - Verify admin is redirected to AdminScreen after login

**Summary**: Verify that a user with the "admin" role is redirected to the AdminScreen after successful login.

**Preconditions**: 
- Admin account exists with "admin" role.
- User is on the Sign In screen.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Enter valid admin credentials             | Credentials are accepted                               |
| 2 | Tap the "Sign In" button                  | Login process initiates                                |
| 3 | Observe the screen after login            | Admin is redirected to the AdminScreen                 |

**Post-conditions**:
- Admin is on the AdminScreen.
- Admin has access to admin functionalities.
