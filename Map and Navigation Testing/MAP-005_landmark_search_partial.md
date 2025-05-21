## Test Case ID: MAP-005_landmark_search_partial
### Title: Landmark Search - Search with partial name or keywords

**Summary**: Verify that searching with a partial name or keywords returns relevant landmarks.

**Preconditions**: 
- User is on the Map Screen.
- Multiple landmarks exist in the system.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Enter a partial name or keyword in the search box | Relevant landmarks matching the query appear in results |
| 2 | Select a landmark from the results        | Map focuses on the selected landmark                    |

**Post-conditions**:
- User can find landmarks using partial names or keywords.
