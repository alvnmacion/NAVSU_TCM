## Test Case ID: ADM-001_admin_login
### Title: Admin Login - Admin user successfully logs in and is directed to AdminScreen

**Summary**: Verify that an admin user can log in and is redirected to the AdminScreen.

**Preconditions**: 
- Admin account exists with valid credentials.
- Admin is on the Sign In screen.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Enter valid admin credentials             | Credentials are accepted                               |
| 2 | Tap the "Sign In" button                  | Login process initiates                                |
| 3 | Observe the screen after login            | Admin is redirected to the AdminScreen                 |

**Post-conditions**:
- Admin session is active.
- Admin has access to admin functionalities.
