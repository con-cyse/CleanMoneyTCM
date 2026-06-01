# SET-001: Update username

Summary: Users can maintain account profile information

Preconditions:

- User is logged in.
- User profile exists in the `users` table.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Settings page. | Username, email, and password cards are displayed. |
| 2 | Enter a new valid username. | Input accepts the value. |
| 3 | Save username change. | Save changes confirmation shows by inputting valid password. |
| 4 | Click confirm. | Success feedback is shown. |
| 5 | Refresh the page. | Updated username remains visible. |

Post-conditions:

- Updated username remains visible.