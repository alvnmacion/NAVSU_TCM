## Test Case ID: REWU-003_redeem_reward_success
### Title: Redeem Reward - Successfully redeem an available reward with sufficient points

**Summary**: Verify that a user can successfully redeem a reward if they have enough points.

**Preconditions**: 
- User is on the Rewards screen.
- User has sufficient points for at least one reward.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Tap on a reward with sufficient points    | Reward details dialog opens                             |
| 2 | Tap the 'Redeem' button                   | Redemption is successful and confirmation is shown      |

**Post-conditions**:
- Reward is marked as redeemed and points are deducted.
