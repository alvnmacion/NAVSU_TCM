## Test Case ID: SEC-006_authentication_robustness
### Title: Authentication Robustness - Test for weak password policies (if custom), session management vulnerabilities (token handling)

**Summary**: Test for weak password policies and session management vulnerabilities.

**Preconditions**: 
- App is installed and running.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Attempt to register with weak passwords   | Registration is blocked or warning is shown             |
| 2 | Inspect session/token handling            | Tokens are securely managed and not leaked              |

**Post-conditions**:
- Authentication is robust and secure.
