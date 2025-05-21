## Test Case ID: ADMR-003_delete_reward
### Title: Delete Reward - Admin deletes a reward from the system after confirmation

**Summary**: Verify that the admin can delete a reward after confirming the action.

**Preconditions**: 
- Admin is logged in and on the Rewards Management tab.
- At least one reward exists.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Select a reward from the list             | Reward details are displayed                            |
| 2 | Tap the 'Delete' button                   | Confirmation dialog appears                             |
| 3 | Confirm the deletion                      | Reward is removed from the system and list              |

**Post-conditions**:
- Deleted reward is no longer available to users.
