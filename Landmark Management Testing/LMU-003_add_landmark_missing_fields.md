## Test Case ID: LMU-003_add_landmark_missing_fields
### Title: Add Landmark - Attempt to submit with missing required fields (name, location coordinates)

**Summary**: Verify that the system prevents submission when required fields are missing.

**Preconditions**: 
- User is on the 'Add Landmark' dialog.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Leave required fields (name, latitude, longitude) empty | Validation errors are shown for missing fields          |
| 2 | Tap the 'Submit' button                   | Submission is blocked and user is prompted to fill required fields |

**Post-conditions**:
- No landmark is created until all required fields are provided.
