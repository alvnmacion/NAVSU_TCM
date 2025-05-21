## Test Case ID: MAP-004_landmark_search_full_name
### Title: Landmark Search - Search for existing approved landmarks by full name

**Summary**: Verify that searching for a landmark by its full name returns the correct result.

**Preconditions**: 
- User is on the Map Screen.
- At least one approved landmark exists in the system.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Enter the full name of an approved landmark in the search box | Landmark appears in the search results                 |
| 2 | Select the landmark from the results      | Map focuses on the selected landmark                    |

**Post-conditions**:
- User can find and select landmarks by full name.
