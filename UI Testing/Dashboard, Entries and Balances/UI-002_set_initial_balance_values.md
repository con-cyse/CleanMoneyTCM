# UI-002: Set initial balance values

Summary: New semester balances can be initialized

Preconditions:

- User is logged in.
- No balance row exists yet for the user's organization and active semester.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Dashboard. | Initial Balance Setup card is displayed. |
| 2 | Enter valid cash on bank, cash on hand, collectibles, fine amount, and total students with fines. | Numeric fields accept valid amounts. |
| 3 | Submit the setup form. | Balance row is saved. |
| 4 | Observe dashboard. | Balance cards replace the setup card and show the saved values. |

Post-conditions:

- A balance row exists for the current semester.