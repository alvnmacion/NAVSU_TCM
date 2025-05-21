## Test Case ID: PERF-005_battery_consumption
### Title: Battery Consumption - Monitor battery usage during 30 mins of active navigation vs idle

**Summary**: Monitor and compare battery usage during 30 minutes of active navigation and 30 minutes of idle app usage.

**Preconditions**: 
- App is installed and device is fully charged.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Use app in active navigation for 30 minutes | Record battery percentage drop                         |
| 2 | Leave app idle on MapScreen for 30 minutes | Record battery percentage drop                         |

**Post-conditions**:
- Battery usage is within acceptable limits for both scenarios.
