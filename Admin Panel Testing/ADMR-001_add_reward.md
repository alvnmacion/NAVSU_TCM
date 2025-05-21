## Test Case ID: ADMR-001_add_reward
### Title: Add Reward - Admin adds a new reward with name, points cost, quantity, image URL, and claim location

**Summary**: Verify that the admin can add a new reward with all required details.

**Preconditions**: 
- Admin is logged in and on the Rewards Management tab.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Tap the 'Add Reward' button               | Add Reward form appears                                 |
| 2 | Enter valid name, points cost, quantity, image URL, and claim location | All fields are accepted with no validation errors       |
| 3 | Tap the 'Save' or 'Add' button            | Reward is added and appears in the rewards list         |

**Post-conditions**:
- New reward is available for users to redeem.
