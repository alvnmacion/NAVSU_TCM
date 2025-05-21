## Test Case ID: ADML-004_delete_landmark
### Title: Delete Landmark - Admin deletes a landmark (pending, approved, or rejected) verify it's removed from system

**Summary**: Verify that the admin can delete any landmark and it is removed from the system.

**Preconditions**: 
- Admin is logged in and on the 'Landmark Approval' tab.
- At least one landmark exists (any status).

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Select any landmark (pending, approved, or rejected) | Landmark details are displayed                         |
| 2 | Tap the 'Delete' button                   | Landmark is removed from the system and no longer visible anywhere |

**Post-conditions**:
- Deleted landmark is not present in any list or on the map.
