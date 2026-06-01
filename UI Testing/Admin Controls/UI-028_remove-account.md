# TC-ADM-005: Remove user account

Summary: Super-admin can remove obsolete accounts

Preconditions:

- Super-admin is logged in.
- Disposable test account exists.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Admin Controls. | Account list is displayed. |
| 2 | Select delete/remove action for the test account. | Confirmation dialog appears. |
| 3 | Confirm removal. | Account is removed from authentication/profile records as configured. |
| 4 | Attempt login with removed account. | Login fails. |

Post-conditions:

- Login fails.