## Test Case ID: SEC-002_input_validation
### Title: Input Validation (Client-side & Server-side) - Test for common vulnerabilities in input fields if applicable

**Summary**: Test input fields for common vulnerabilities (e.g., XSS, SQL injection) and verify both client-side and server-side validation.

**Preconditions**: 
- App is installed and running.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Enter malicious input in fields (e.g., scripts, SQL) | Input is sanitized or rejected; app remains secure     |

**Post-conditions**:
- App is not vulnerable to common input attacks.
