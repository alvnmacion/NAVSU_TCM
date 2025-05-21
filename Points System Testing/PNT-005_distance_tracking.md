## Test Case ID: PNT-005_distance_tracking
### Title: Distance Tracking - Verify 'distance' field in user's document updates correctly

**Summary**: Ensure the 'distance' field in the user's document is updated accurately as the user travels.

**Preconditions**: 
- User is logged in.
- User starts and completes or cancels navigation.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Start navigation and travel a distance    | 'distance' field increases according to distance covered|
| 2 | Complete or cancel navigation             | 'distance' field reflects total distance for the session|

**Post-conditions**:
- User's total distance is always accurate and up-to-date.
