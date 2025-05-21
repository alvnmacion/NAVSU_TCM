## Test Case ID: MAP-020_map_rotation
### Title: Map Rotation - Verify map rotates with compass heading during navigation (if feature exists)

**Summary**: Verify that the map rotates to match the device's compass heading during navigation.

**Preconditions**: 
- User is in active navigation mode.
- Device has a compass sensor.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Rotate the device while navigating        | Map rotates to match compass heading                    |

**Post-conditions**:
- Map orientation matches device heading.
