## Test Case ID: MAP-002_current_location
### Title: Current Location - Verify current location blue dot is accurately displayed and updates

**Summary**: Ensure the user's current location is shown as a blue dot and updates as the user moves.

**Preconditions**: 
- User is logged in and on the Map Screen.
- Location services are enabled and granted.
- Internet connection is available.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Observe the map after loading             | Blue dot appears at user's current location             |
| 2 | Move to a different physical location     | Blue dot updates position in real-time                  |

**Post-conditions**:
- User's current location is always accurately reflected on the map.
