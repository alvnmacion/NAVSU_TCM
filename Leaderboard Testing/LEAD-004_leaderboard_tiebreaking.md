## Test Case ID: LEAD-004_leaderboard_tiebreaking
### Title: Leaderboard Tie-breaking - Verify handling of tied ranks (users with the same distance share the same rank)

**Summary**: Verify that users with the same total distance share the same rank on the leaderboard.

**Preconditions**: 
- User is on the Leaderboard screen.
- At least two users have the same total distance.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Observe users with identical distances    | Users share the same rank number                        |
| 2 | Observe the next user                     | Next rank is incremented appropriately (e.g., 1, 2, 2, 4) |

**Post-conditions**:
- Tie-breaking is handled correctly and fairly.
