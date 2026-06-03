# UI-007: Delete ledger entry

Summary: Users can remove incorrect ledger entries before publishing

Preconditions:

- User is logged in.
- At least one test entry exists.
- Dashboard is unlocked.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Select delete for a test entry. | Confirmation dialog appears. |
| 2 | Confirm deletion. | Entry is removed from the table. |
| 3 | Observe balances. | Balance totals refresh to exclude the deleted entry. |

Post-conditions:

- Deleted entry is no longer present in the database.