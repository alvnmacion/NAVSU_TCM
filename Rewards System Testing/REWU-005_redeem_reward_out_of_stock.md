## Test Case ID: REWU-005_redeem_reward_out_of_stock
### Title: Redeem Reward (Out of Stock) - Attempt to redeem a reward with quantity zero verify it's not possible or shown as unavailable

**Summary**: Verify that rewards with zero quantity cannot be redeemed or are shown as unavailable.

**Preconditions**: 
- User is on the Rewards screen.
- At least one reward has quantity zero.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Observe rewards with quantity zero        | Reward is shown as unavailable or disabled              |
| 2 | Attempt to redeem the out-of-stock reward | Redemption is blocked or not possible                   |

**Post-conditions**:
- User cannot redeem out-of-stock rewards.
