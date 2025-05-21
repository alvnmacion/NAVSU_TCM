## Test Case ID: ADML-001_view_pending_landmarks
### Title: View Pending Landmarks - Admin views list of landmarks with 'pending' status in 'Landmark Approval' or 'Pending Landmarks' tab

**Summary**: Verify that the admin can view a list of all landmarks with 'pending' status in the appropriate admin tab.

**Preconditions**: 
- Admin is logged in and on the AdminScreen.
- At least one landmark has 'pending' status.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Navigate to the 'Landmark Approval' or 'Pending Landmarks' tab | List of all pending landmarks is displayed             |

**Post-conditions**:
- Admin can see all pending landmarks awaiting review.
