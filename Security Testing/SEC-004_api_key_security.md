## Test Case ID: SEC-004_api_key_security
### Title: API Key Security - Verify API keys (e.g. OpenRouteService) are not exposed client-side if they should be server-side or are appropriately secured

**Summary**: Ensure that API keys are not exposed in the client if they should be server-side, or are otherwise secured.

**Preconditions**: 
- App is installed and running.
- Access to app package/bundle for inspection.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Inspect app bundle and network requests   | API keys are not exposed or are properly obfuscated     |

**Post-conditions**:
- API keys are not accessible to unauthorized parties.
