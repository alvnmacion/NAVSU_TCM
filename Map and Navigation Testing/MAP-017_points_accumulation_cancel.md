## Test Case ID: MAP-017_points_accumulation_cancel
### Title: Points Accumulation (Cancel Navigation) - Verify points for distance covered are awarded if navigation is cancelled midway

**Summary**: Verify that points are still awarded for distance covered if navigation is cancelled before reaching the destination.

**Preconditions**: 
- User starts navigation but cancels before arrival.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Cancel navigation before reaching destination | Points are awarded for distance covered so far         |
| 2 | Check user points balance                 | Points balance reflects partial journey                 |

**Post-conditions**:
- User receives partial points for incomplete navigation.
