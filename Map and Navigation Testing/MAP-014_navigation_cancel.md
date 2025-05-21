## Test Case ID: MAP-014_navigation_cancel
### Title: Navigation Cancel - Cancel navigation midway using the cancel option

**Summary**: Verify that navigation can be cancelled at any time and the app returns to normal map mode.

**Preconditions**: 
- User is in active navigation mode.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Tap the 'Cancel Navigation' button        | Navigation ends and map returns to normal mode          |

**Post-conditions**:
- Navigation UI is dismissed.
- User can start a new navigation if desired.
