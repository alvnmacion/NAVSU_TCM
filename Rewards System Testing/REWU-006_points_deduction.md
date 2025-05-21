## Test Case ID: REWU-006_points_deduction
### Title: Points Deduction - Verify user's points are correctly deducted after successful redemption request (status pending)

**Summary**: Verify that points are deducted from the user's balance after a successful redemption request.

**Preconditions**: 
- User is on the Rewards screen.
- User has sufficient points and redeems a reward.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Redeem a reward                           | Points are deducted immediately and status is set to pending |

**Post-conditions**:
- Points balance reflects the deduction.
