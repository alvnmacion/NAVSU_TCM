## Test Case ID: ADMR-005_reward_form_validation
### Title: Reward Form Validation - Verify validation for required fields and correct data types in add/edit reward form

**Summary**: Verify that the add/edit reward form validates required fields and data types.

**Preconditions**: 
- Admin is logged in and on the Rewards Management tab.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Leave required fields empty or enter invalid data types | Validation errors are shown for each issue              |
| 2 | Correct the errors and submit             | Form is accepted and reward is added/updated            |

**Post-conditions**:
- Only valid rewards can be added or updated.
