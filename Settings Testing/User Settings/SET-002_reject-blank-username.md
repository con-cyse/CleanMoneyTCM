# SET-002: Reject blank username

Summary: Save changes remains disabled when the username field is empty

Preconditions:

- User is logged in.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Settings page. | Username card is displayed. |
| 2 | Clear the username field. | Field becomes empty. |
| 3 | Observe the Save Changes button. | The Save Changes button is disabled. |

Post-conditions:

- No changes can be saved while the username field is empty.