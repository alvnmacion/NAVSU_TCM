## Test Case ID: ADMRA-003_reject_redemption
### Title: Reject Redemption - Admin rejects a pending redemption status changes to 'rejected', points potentially refunded (verify logic), user notified (if applicable)

**Summary**: Verify that rejecting a pending redemption updates its status to 'rejected', points are refunded if applicable, and user is notified.

**Preconditions**: 
- Admin is logged in and on the Rewards Approval tab.
- At least one redemption request is pending.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Select a pending redemption request       | Redemption details are displayed                        |
| 2 | Tap the 'Reject' button                   | Status changes to 'rejected', points refunded if logic applies, user is notified if feature exists |

**Post-conditions**:
- Redemption is marked as rejected, points refunded if applicable, and user is notified.
