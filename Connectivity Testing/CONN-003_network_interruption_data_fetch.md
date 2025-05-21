## Test Case ID: CONN-003_network_interruption_data_fetch
### Title: Network Interruption (Data Fetch) - Behavior if network drops while fetching data (leaderboard, rewards)

**Summary**: Verify the app's behavior if the network drops while fetching data such as leaderboard or rewards.

**Preconditions**: 
- Device has internet connection initially.
- User is about to fetch data (e.g., open Leaderboard or Rewards).

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Navigate to Leaderboard or Rewards screen | Data fetch begins                                      |
| 2 | Disable internet during fetch             | App shows error message or fallback to cached data      |

**Post-conditions**:
- User is informed of the issue and can view cached data if available.
