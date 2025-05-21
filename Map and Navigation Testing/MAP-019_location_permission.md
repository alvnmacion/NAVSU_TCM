## Test Case ID: MAP-019_location_permission
### Title: Location Permission - Handle location permission denied, granted, and denied forever scenarios

**Summary**: Verify the app handles all location permission states appropriately.

**Preconditions**: 
- User is on the Map Screen.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Deny location permission                  | App shows appropriate message and disables location features |
| 2 | Grant location permission                 | App enables location features and shows current location |
| 3 | Deny forever (never ask again)            | App shows instructions to enable permission in settings |

**Post-conditions**:
- App responds correctly to all permission states.
