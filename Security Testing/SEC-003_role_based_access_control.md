## Test Case ID: SEC-003_role_based_access_control
### Title: Role-Based Access Control - Rigorously test that users cannot access admin functionalities or data, and admins cannot impersonate users without due process

**Summary**: Ensure that only authorized users can access admin features/data, and admins cannot impersonate users without proper process.

**Preconditions**: 
- App is installed and running.
- Both user and admin accounts exist.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Attempt to access admin features as a regular user | Access is denied; user cannot view or modify admin data|
| 2 | Attempt to impersonate another user as admin | Action is blocked or requires explicit process/logging |

**Post-conditions**:
- Role-based access is strictly enforced.
