## Test Case ID: MAP-001_map_display_initial
### Title: Map Display - Verify map loads correctly with initial view

**Summary**: Verify that the map loads with the default zoom and is centered on the user's current location or a default region.

**Preconditions**: 
- User is logged in to the NAVSU app.
- Internet connection is available.
- Location services are enabled.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Navigate to Map Screen after login        | Map loads with proper tiles and formatting              |
| 2 | Observe initial map view                  | Map shows default zoom level as configured              |
| 3 | Check if map is centered appropriately    | Map is centered on user's current location or default region |
| 4 | Observe map controls and interface        | Navigation controls, search box, and menu are visible   |

**Post-conditions**:
- Map is displayed properly with the correct style and layout.
- User can interact with the map through standard gestures.
