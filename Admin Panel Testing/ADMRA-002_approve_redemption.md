## Test Case ID: ADMRA-002_approve_redemption
### Title: Approve Redemption - Admin approves a pending redemption status changes to 'completed' (or 'approved'), user notified (if applicable)

**Summary**: Verify that approving a pending redemption updates its status to 'completed' (or 'approved') and notifies the user if applicable.

**Preconditions**: 
- Admin is logged in and on the Rewards Approval tab.
- At least one redemption request is pending.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Select a pending redemption request       | Redemption details are displayed                        |
| 2 | Tap the 'Approve' button                  | Status changes to 'completed' (or 'approved'), user is notified if feature exists |

**Post-conditions**:
- Redemption is marked as approved and user is notified.
