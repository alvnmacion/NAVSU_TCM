## Test Case ID: ADMR-002_edit_reward
### Title: Edit Reward - Admin edits details of an existing reward

**Summary**: Verify that the admin can edit the details of an existing reward.

**Preconditions**: 
- Admin is logged in and on the Rewards Management tab.
- At least one reward exists.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Select a reward from the list             | Reward details are displayed in editable form           |
| 2 | Edit any field (name, points, quantity, image, location) | Changes are accepted and validated                     |
| 3 | Tap the 'Save' button                     | Reward details are updated in the list                  |

**Post-conditions**:
- Reward reflects the updated details.
