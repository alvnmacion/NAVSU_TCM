## Test Case ID: ADM-003_admin_logout
### Title: Admin Logout - Admin user successfully logs out via the header logout button

**Summary**: Verify that the admin can log out using the header logout button.

**Preconditions**: 
- Admin is logged in and on the AdminScreen.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Tap the header logout button              | Logout process initiates and admin is redirected to Sign In screen |

**Post-conditions**:
- Admin session is terminated.
- Admin must log in again to access admin features.
