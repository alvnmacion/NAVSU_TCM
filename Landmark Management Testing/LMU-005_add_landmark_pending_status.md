## Test Case ID: LMU-005_add_landmark_pending_status
### Title: Add Landmark - Verify landmark is submitted with 'pending' status and creator ID

**Summary**: Verify that a newly submitted landmark is created with a 'pending' status and is associated with the submitting user's ID.

**Preconditions**: 
- User is on the 'Add Landmark' dialog.
- User submits a valid landmark.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Submit a valid landmark                   | Landmark is created with 'pending' status and creator ID is recorded |

**Post-conditions**:
- Landmark is not immediately approved or visible to all users.
- Creator can view the status of their submission.
