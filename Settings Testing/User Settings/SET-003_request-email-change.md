# SET-003: Request email change

Summary: Users can update account email securely

Preconditions:

- User is logged in.
- New email address is not already used by another account.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Settings page. | Email card displays current email. |
| 2 | Enter a valid new email. | Email field accepts the new address. |
| 3 | Submit the update. | System initiates the configured email change flow. |
| 4 | Confirm from email if required by Supabase. | Account email changes only after required verification. |

Post-conditions:

- Account email changes only after required verification.