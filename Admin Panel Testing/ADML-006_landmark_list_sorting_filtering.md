## Test Case ID: ADML-006_landmark_list_sorting_filtering
### Title: Landmark List Sorting/Filtering - Verify landmarks are sorted (e.g. by creation date) and if any filters are available

**Summary**: Verify that the landmark list is sorted (e.g., by creation date) and that any available filters work as expected.

**Preconditions**: 
- Admin is logged in and on the 'Landmark Approval' tab.
- Multiple landmarks exist.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Observe the list of landmarks             | Landmarks are sorted by the default (e.g., creation date descending) |
| 2 | Apply available filters (e.g., status)    | List updates to show only landmarks matching the filter |

**Post-conditions**:
- Sorting and filtering work as intended.
