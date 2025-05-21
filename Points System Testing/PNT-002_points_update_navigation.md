## Test Case ID: PNT-002_points_update_navigation
### Title: Points Update (Navigation) - Verify points update in real-time or after navigation completion/cancellation

**Summary**: Verify that points are updated in real-time or immediately after navigation is completed or cancelled.

**Preconditions**: 
- User is logged in.
- User starts navigation to a landmark.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Complete navigation to a landmark         | Points increase according to distance traveled          |
| 2 | Cancel navigation before completion       | Points increase based on partial distance covered       |
| 3 | Observe points on all relevant screens    | Updated points are reflected everywhere immediately     |

**Post-conditions**:
- Points reflect the latest navigation activity.
