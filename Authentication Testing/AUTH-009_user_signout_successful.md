## Test Case ID: AUTH-009_user_signout_successful
### Title: User Sign Out - Successful logout from user account

**Summary**: Verify that a logged-in user can successfully log out.

**Preconditions**: 
- User is logged in to the NAVSU app.
- User is on any screen with access to logout.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Tap the "Logout" or "Sign Out" button     | Logout process initiates                               |
| 2 | Observe the response                      | User is redirected to the Sign In screen               |
| 3 | Try accessing authenticated features      | Access is denied, user must log in again               |

**Post-conditions**:
- User session is terminated.
- User must log in to access protected features.
