## Test Case ID: PERF-007_ui_responsiveness_under_load
### Title: UI Responsiveness under Load - App remains responsive when loading large lists or performing background tasks

**Summary**: Verify that the app remains responsive when handling large data sets or background operations.

**Preconditions**: 
- App is installed and running.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Load large lists (e.g., Leaderboard, Rewards, Admin lists) | App remains responsive and does not freeze             |
| 2 | Perform background tasks (e.g., navigation, data sync) while interacting with UI | UI remains smooth and responsive                  |

**Post-conditions**:
- App is usable and responsive under heavy load.
