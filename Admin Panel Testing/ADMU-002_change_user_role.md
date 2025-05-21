## Test Case ID: ADMU-002_change_user_role
### Title: Change User Role - Admin changes a user's role (e.g. 'user' to 'admin' or vice-versa) via confirmation dialog

**Summary**: Verify that the admin can change a user's role via a confirmation dialog.

**Preconditions**: 
- Admin is logged in and on the User Authorization tab.
- At least one user is listed.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Select a user from the list               | User details are displayed                              |
| 2 | Tap the 'Change Role' button              | Confirmation dialog appears                             |
| 3 | Confirm the role change                   | User's role is updated and reflected in the list        |

**Post-conditions**:
- User's new role is saved and visible to admin.
