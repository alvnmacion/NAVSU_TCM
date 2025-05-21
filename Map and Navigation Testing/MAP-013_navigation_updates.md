## Test Case ID: MAP-013_navigation_updates
### Title: Navigation Updates - Verify map follows user movement and updates route/ETA if user deviates

**Summary**: Verify that the map and navigation instructions update as the user moves or deviates from the route.

**Preconditions**: 
- User is in active navigation mode.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Move along the route                      | Map follows user and updates ETA/distance               |
| 2 | Deviate from the suggested route          | Route recalculates and navigation updates accordingly   |

**Post-conditions**:
- Navigation remains accurate and responsive to user movement.
