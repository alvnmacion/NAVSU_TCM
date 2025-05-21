## Test Case ID: PNT-004_points_history
### Title: Points History - Verify 'points_history' collection records transactions (distance, redemption)

**Summary**: Verify that all points transactions (navigation, redemption) are recorded in the 'points_history' collection.

**Preconditions**: 
- User is logged in.
- User performs navigation and/or reward redemption.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Complete a navigation or redeem a reward  | A new entry is added to the 'points_history' collection |
| 2 | View points history                       | All transactions are listed with correct details        |

**Post-conditions**:
- All points-related activities are traceable in the history.
