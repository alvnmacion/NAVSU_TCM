## Test Case ID: SEC-007_firestore_security_rules
### Title: Firestore Security Rules - Review and test Firestore security rules to prevent unauthorized data access/modification

**Summary**: Review and test Firestore security rules to ensure only authorized users can access or modify data.

**Preconditions**: 
- App is installed and running.
- Access to Firestore security rules.

**Scenario 1**

| # | Step                                      | Expected Behavior                                       |
|---|-------------------------------------------|--------------------------------------------------------|
| 1 | Attempt unauthorized data access/modification | Access is denied by Firestore security rules           |
| 2 | Attempt authorized actions                | Access is granted as per rules                          |

**Post-conditions**:
- Firestore security rules are effective and enforced.
