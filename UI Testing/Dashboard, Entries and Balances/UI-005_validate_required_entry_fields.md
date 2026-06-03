# UI-005: Validate required entry fields

Summary: Ledger entries must contain complete required details

Preconditions:

- User is logged in.
- Dashboard is unlocked.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Add Entry sheet. | Blank form is displayed. |
| 2 | Leave category, description, date, unit price, or quantity blank. | Blank fields remain visible. |
| 3 | Click `Save`. | Required fields are marked as invalid and no entry is saved. |
| 4 | Fill all required fields with valid values. | Validation indicators clear as fields are corrected. |

Post-conditions:

- Validation indicators clear as fields are corrected.