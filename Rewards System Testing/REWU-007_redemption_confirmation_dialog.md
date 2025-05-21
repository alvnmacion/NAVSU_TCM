## Test Case ID: REWU-007_redemption_confirmation_dialog
### Title: Redemption Confirmation Dialog - Verify confirmation dialog shows reward details and remaining points before redeeming

**Summary**: Verify that a confirmation dialog appears before redeeming, showing reward details and remaining points.

**Preconditions**: 
- User is on the Rewards screen.
- User has sufficient points for a reward.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Tap 'Redeem' on a reward                  | Confirmation dialog appears with reward details and remaining points |
| 2 | Confirm redemption                        | Redemption proceeds if confirmed                        |

**Post-conditions**:
- User is informed before points are deducted.
