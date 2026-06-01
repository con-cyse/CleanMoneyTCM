# TC-REP-002: Auto-generate report fields from ledger data

Summary: Report publishing can auto-fill values from computed ledger totals

Preconditions:

- User is logged in.
- Ledger entries include at least one income and one expense.
- Balance row exists.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Publish dialog. | Publish form appears. |
| 2 | Trigger auto-generate. | Certification and numeric report fields are populated from application data. |
| 3 | Compare generated totals with dashboard totals. | Income, expense, and balance totals are consistent. |
| 4 | Edit an allowed certification field. | Manual correction is accepted before publishing. |

Post-conditions:

- Manual correction is accepted before publishing.