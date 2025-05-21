## Test Case ID: ADML-002_approve_landmark
### Title: Approve Landmark - Admin approves a pending landmark verify status changes to 'approved' and landmark appears on map for users

**Summary**: Verify that approving a pending landmark updates its status to 'approved' and makes it visible on the map for users.

**Preconditions**: 
- Admin is logged in and on the 'Landmark Approval' tab.
- At least one landmark is pending approval.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Select a pending landmark                 | Landmark details are displayed                          |
| 2 | Tap the 'Approve' button                  | Status changes to 'approved' and landmark appears on user map |

**Post-conditions**:
- Approved landmark is visible to all users.
