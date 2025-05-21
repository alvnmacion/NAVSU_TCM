## Test Case ID: REWU-004_redeem_reward_insufficient_points
### Title: Redeem Reward (Insufficient Points) - Attempt to redeem a reward with insufficient points verify error/dialog

**Summary**: Verify that attempting to redeem a reward without enough points shows an error or dialog.

**Preconditions**: 
- User is on the Rewards screen.
- User has fewer points than required for at least one reward.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Tap on a reward with insufficient points  | Reward details dialog opens                             |
| 2 | Tap the 'Redeem' button                   | Error or dialog appears indicating insufficient points  |

**Post-conditions**:
- Redemption is blocked until user has enough points.
