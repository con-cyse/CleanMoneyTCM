# TC-REP-004: Replace existing same-semester report

Summary: Publishing supports upsert/replacement for same-semester reports

Preconditions:

- A report is already published for the user's organization and semester.
- User has permission to publish or republish.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Publish dialog for the same semester. | Existing publication state is recognized. |
| 2 | Publish a revised report. | Application replaces the same-semester report instead of creating duplicate official entries. |
| 3 | Open Reports page. | Only the latest intended report is visible for that same scope and semester. |

Post-conditions:

- Only the latest intended report is visible for that same scope and semester.