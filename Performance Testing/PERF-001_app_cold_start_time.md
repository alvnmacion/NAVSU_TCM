## Test Case ID: PERF-001_app_cold_start_time
### Title: App Cold Start Time - Measure time from app launch (killed state) to interactive MapScreen/AdminScreen

**Summary**: Measure the time taken from launching the app (from a killed state) to when the MapScreen or AdminScreen becomes interactive.

**Preconditions**: 
- App is installed and not running in the background.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Launch the app from a killed state        | Timer starts                                            |
| 2 | Wait until MapScreen/AdminScreen is interactive | Timer stops; record the elapsed time                |

**Post-conditions**:
- Cold start time is within acceptable limits (e.g., < 3 seconds).
