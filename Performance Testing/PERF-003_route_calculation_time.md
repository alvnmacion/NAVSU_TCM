## Test Case ID: PERF-003_route_calculation_time
### Title: Route Calculation Time - Time taken to calculate and display routes for short, medium, and long distances

**Summary**: Measure the time taken to calculate and display routes of varying distances.

**Preconditions**: 
- App is installed and user is on the MapScreen.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Select a nearby landmark and start navigation | Route is calculated and displayed quickly             |
| 2 | Select a medium-distance landmark and start navigation | Route is calculated and displayed quickly         |
| 3 | Select a distant landmark and start navigation | Route is calculated and displayed quickly           |

**Post-conditions**:
- Route calculation time is within acceptable limits for all distances.
