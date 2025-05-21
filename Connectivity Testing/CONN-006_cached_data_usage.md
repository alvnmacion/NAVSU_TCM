## Test Case ID: CONN-006_cached_data_usage
### Title: Cached Data Usage - Verify use of cached data (user points/distance from SharedPreferences) when offline or before fresh data loads

**Summary**: Verify that the app uses cached data (e.g., user points, distance) from SharedPreferences when offline or before fresh data loads.

**Preconditions**: 
- App has previously cached data.
- Device is offline or network is slow.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Launch the app or navigate to relevant screens | Cached data is displayed immediately                   |
| 2 | Wait for network or reconnect             | Fresh data replaces cached data when available          |

**Post-conditions**:
- User always sees the most recent available data, even when offline.
