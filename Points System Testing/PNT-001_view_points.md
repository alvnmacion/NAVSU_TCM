## Test Case ID: PNT-001_view_points
### Title: View Points - Verify user's current points are displayed consistently (Map Screen, Leaderboard, Rewards Screen)

**Summary**: Ensure the user's current points are displayed accurately and consistently across all relevant screens.

**Preconditions**: 
- User is logged in.
- User has a non-zero points balance.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Observe points on the Map Screen          | Points value is displayed and matches backend           |
| 2 | Navigate to the Leaderboard               | Points value matches that on the Map Screen             |
| 3 | Navigate to the Rewards Screen            | Points value matches that on the other screens          |

**Post-conditions**:
- Points are consistent and up-to-date on all screens.
