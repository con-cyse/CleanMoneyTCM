# UI-009: Preview financial report PDF

Summary: Users can preview generated financial reports

Preconditions:

- User is logged in.
- Ledger and balance data exist for the current semester.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Dashboard. | Welcome card displays report actions. |
| 2 | Click report preview action. | PDF preview dialog/card opens. |
| 3 | Wait for PDF generation. | Generated financial report loads without template errors. |
| 4 | Review totals and category sections. | Values match current income, expense, balance, and control number data. |

Post-conditions:

- Values match current income, expense, balance, and control number data.