# TC-REP-006: Reject publishing with missing required data

Summary: Official reports require complete certification and financial data

Preconditions:

- User is logged in.
- Publish dialog can be opened.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Publish dialog. | Required fields are visible. |
| 2 | Clear one or more required fields. | Field remains blank. |
| 3 | Click Publish. | Validation prevents publication. |
| 4 | Check Reports page and public viewer. | No new official report appears. |

Post-conditions:

- No new official report appears.