# NAVSU App Test Coverage Report

## Authentication Testing

| Test Case ID | Title                                                        | Covered |
|--------------|--------------------------------------------------------------|---------|
| AUTH-001     | User Sign Up - Successful registration                       |   ✅    |
| AUTH-002     | User Sign Up - Attempt registration with existing email      |   ✅    |
| AUTH-003     | User Sign Up - Attempt registration with invalid email format|   ✅    |
| AUTH-004     | User Sign Up - Attempt registration with weak password       |   ✅    |
| AUTH-005     | User Sign In - Successful login (user role)                  |   ✅    |
| AUTH-006     | User Sign In - Successful login (admin role)                 |   ✅    |
| AUTH-007     | User Sign In - Incorrect password                            |   ✅    |
| AUTH-008     | User Sign In - Non-existent email                            |   ✅    |
| AUTH-009     | User Sign Out - Successful logout (user)                     |   ✅    |
| AUTH-010     | User Sign Out - Successful logout (admin)                    |   ✅    |
| AUTH-011     | Session Management - Persistence after app close/reopen      |   ✅    |
| AUTH-012     | Role Redirection - User to MapScreen                         |   ✅    |
| AUTH-013     | Role Redirection - Admin to AdminScreen                      |   ✅    |

All critical authentication flows are covered.
