# SET-005: Reject mismatched or weak password

Summary: Password changes must enforce security rules

Preconditions:

- User is logged in.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Settings page. | Password card is visible. |
| 2 | Enter a weak password or mismatched confirmation. | Fields accept entry for validation. |
| 3 | Save password change. | Application rejects the update and shows an actionable error. |
| 4 | Log out and attempt login with the rejected password. | Login fails because password was not changed. |

Post-conditions:

- Login fails because password was not changed.