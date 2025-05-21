## Test Case ID: LMU-002_add_landmark_valid
### Title: Add Landmark - Submit new landmark with valid name, description, latitude, longitude, and image

**Summary**: Verify that a new landmark can be submitted with all valid required fields.

**Preconditions**: 
- User is on the 'Add Landmark' dialog.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Enter a valid name, description, latitude, longitude, and select an image | All fields are accepted with no validation errors       |
| 2 | Tap the 'Submit' button                   | Landmark is submitted and confirmation is shown         |

**Post-conditions**:
- New landmark is created and visible in the system (pending approval if applicable).
