# UI-029: End semester

Summary: Super-admin can close a semester and prevent further edits

Preconditions:

- Super-admin is logged in.
- Active semester exists.
- Test organization has ledger entries.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Admin Controls. | Semester card is visible. |
| 2 | Start End Semester action. | Confirmation dialog appears. |
| 3 | Confirm the semester end. | Active semester is marked ended. |
| 4 | Log in as a regular user and open Dashboard. | Dashboard reflects ended-semester state and prevents ledger edits. |

Post-conditions:

- Dashboard reflects ended-semester state and prevents ledger edits.