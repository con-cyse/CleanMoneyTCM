# UI-004: Add batch mixed entries

Summary: Users can add multiple ledger entries in one transaction flow

Preconditions:

- User is logged in.
- Dashboard is unlocked.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Add Entry sheet. | One blank entry form is displayed. |
| 2 | Fill a valid income entry. | Income control number is assigned. |
| 3 | Click `Add Another Entry`. | A second blank entry form appears below the first. |
| 4 | Fill a valid expense entry. | Expense control number is assigned independently from income. |
| 5 | Click `Save`. | Both entries are saved and their respective tables refresh. |

Post-conditions:

- Both entries are saved and their respective tables refresh.