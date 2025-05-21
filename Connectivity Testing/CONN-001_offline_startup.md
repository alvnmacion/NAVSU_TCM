## Test Case ID: CONN-001_offline_startup
### Title: Offline Startup - App behavior when launched without internet (cached data display, error messages)

**Summary**: Verify the app's behavior when launched without an internet connection, including display of cached data and error messages.

**Preconditions**: 
- Device is offline (no internet connection).
- App has been used previously with data cached.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Launch the app with no internet           | App loads and displays cached data if available         |
| 2 | Attempt to access features requiring fresh data | Error messages or offline indicators are shown      |

**Post-conditions**:
- User is informed of offline status and can view cached data.
