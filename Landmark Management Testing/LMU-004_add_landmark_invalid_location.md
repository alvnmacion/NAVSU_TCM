## Test Case ID: LMU-004_add_landmark_invalid_location
### Title: Add Landmark - Attempt to submit with invalid location data (e.g. out of bounds coordinates)

**Summary**: Verify that the system prevents submission when location data is invalid (e.g., latitude or longitude out of bounds).

**Preconditions**: 
- User is on the 'Add Landmark' dialog.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Enter invalid latitude or longitude values (e.g., latitude > 90 or longitude > 180) | Validation errors are shown for invalid coordinates     |
| 2 | Tap the 'Submit' button                   | Submission is blocked until valid coordinates are entered|

**Post-conditions**:
- No landmark is created with invalid location data.
