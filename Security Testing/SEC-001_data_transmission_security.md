## Test Case ID: SEC-001_data_transmission_security
### Title: Data Transmission Security - Verify all communication with backend (Firebase) and third-party APIs (OpenRouteService) uses HTTPS

**Summary**: Ensure that all data transmitted between the app, backend (Firebase), and third-party APIs is encrypted using HTTPS.

**Preconditions**: 
- App is installed and running.
- Network traffic can be monitored (e.g., using a proxy tool).

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Perform actions that trigger backend/API requests | All requests use HTTPS (no plain HTTP traffic)         |

**Post-conditions**:
- No sensitive data is transmitted over unencrypted channels.
