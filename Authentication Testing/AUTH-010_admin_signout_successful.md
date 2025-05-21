## Test Case ID: AUTH-010_admin_signout_successful
### Title: User Sign Out - Successful logout from admin account

**Summary**: Verify that a logged-in admin can successfully log out.

**Preconditions**: 
- Admin is logged in to the NAVSU app.
- Admin is on any screen with access to logout.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Tap the "Logout" or "Sign Out" button     | Logout process initiates                               |
| 2 | Observe the response                      | Admin is redirected to the Sign In screen              |
| 3 | Try accessing admin features              | Access is denied, must log in again                    |

**Post-conditions**:
- Admin session is terminated.
- Admin must log in to access admin features.
