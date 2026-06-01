# SET-004: Change password with valid input

Summary: Users can rotate passwords

Preconditions:

- User is logged in.
- Password policy is known.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Settings page. | Password card is visible. |
| 2 | Enter a new password that satisfies policy. | Password field accepts the value. |
| 3 | Confirm the new password if confirmation field is available. | Confirmation matches. |
| 4 | Save password change. | Success feedback is shown and future login requires the new password. |

Post-conditions:

- Success feedback is shown and future login requires the new password.