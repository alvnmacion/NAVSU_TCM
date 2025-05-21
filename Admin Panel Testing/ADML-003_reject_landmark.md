## Test Case ID: ADML-003_reject_landmark
### Title: Reject Landmark - Admin rejects a pending landmark verify status changes to 'rejected' and landmark does not appear on map

**Summary**: Verify that rejecting a pending landmark updates its status to 'rejected' and it does not appear on the map.

**Preconditions**: 
- Admin is logged in and on the 'Landmark Approval' tab.
- At least one landmark is pending approval.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Select a pending landmark                 | Landmark details are displayed                          |
| 2 | Tap the 'Reject' button                   | Status changes to 'rejected' and landmark is not shown on user map |

**Post-conditions**:
- Rejected landmark is not visible to users.
