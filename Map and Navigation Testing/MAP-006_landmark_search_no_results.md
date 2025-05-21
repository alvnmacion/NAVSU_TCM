## Test Case ID: MAP-006_landmark_search_no_results
### Title: Landmark Search - Handle no results found for search query

**Summary**: Verify that the app handles cases where no landmarks match the search query.

**Preconditions**: 
- User is on the Map Screen.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Enter a random or invalid string in the search box | No results are found                                   |
| 2 | Observe the search results area           | User sees a 'No results found' message                 |

**Post-conditions**:
- User is clearly informed when no landmarks match the search.
