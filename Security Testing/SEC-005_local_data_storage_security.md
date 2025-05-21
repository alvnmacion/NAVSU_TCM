## Test Case ID: SEC-005_local_data_storage_security
### Title: Local Data Storage Security - Verify sensitive data stored locally (SharedPreferences like UID, tokens) is handled appropriately

**Summary**: Ensure that sensitive data stored locally (e.g., UID, tokens) is handled securely and not accessible to unauthorized apps.

**Preconditions**: 
- App is installed and running.
- Device access for file inspection.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Inspect local storage (SharedPreferences, files) | Sensitive data is encrypted or protected               |

**Post-conditions**:
- Sensitive data is not exposed or easily accessible.
