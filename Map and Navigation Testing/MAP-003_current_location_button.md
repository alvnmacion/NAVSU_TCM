## Test Case ID: MAP-003_current_location_button
### Title: Current Location Button - Verify 'center on current location' button functionality

**Summary**: Verify that tapping the 'center on current location' button recenters the map on the user's current position.

**Preconditions**: 
- User is logged in and on the Map Screen.
- Location services are enabled and granted.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Pan the map away from current location    | Map view moves away from blue dot                       |
| 2 | Tap the 'center on current location' button | Map recenters on user's current location               |

**Post-conditions**:
- Map view is centered on the user's current location.
