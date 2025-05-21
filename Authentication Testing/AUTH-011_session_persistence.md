## Test Case ID: AUTH-011_session_persistence
### Title: Session Management - Verify session persistence after app close and reopen

**Summary**: Verify that the user session persists after closing and reopening the app.

**Preconditions**: 
- User is logged in to the NAVSU app.
- App is running in the foreground.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Close the NAVSU app completely            | App is terminated                                      |
| 2 | Reopen the NAVSU app                      | App launches and checks session                        |
| 3 | Observe the landing screen                | User is still logged in and redirected to appropriate screen |

**Post-conditions**:
- User session remains active.
- User does not need to log in again unless session expired.
