# UI-027: Reject duplicate account creation

Summary: Account provisioning prevents duplicates

Preconditions:

- Super-admin is logged in.
- Email address already belongs to an existing user.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Add Account dialog. | Form appears. |
| 2 | Enter an existing email address. | Field accepts value for validation. |
| 3 | Submit the form. | System rejects the duplicate account and displays an error. |
| 4 | Check account list. | No duplicate user row is added. |

Post-conditions:

- No duplicate user row is added.