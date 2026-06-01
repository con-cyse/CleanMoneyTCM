# TC-REP-005: Unpublish report

Summary: Users can remove a published report when correction is needed

Preconditions:

- User is logged in.
- Organization has a published report.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Dashboard. | Unpublish action is visible for published report state. |
| 2 | Click Unpublish. | Confirmation dialog appears. |
| 3 | Confirm unpublish. | Report publication is removed. |
| 4 | Check dashboard mutation controls. | Dashboard returns to editable state if semester is not ended. |
| 5 | Check public viewer for the same filters. | Public viewer no longer displays the unpublished report. |

Post-conditions:

- Public viewer no longer displays the unpublished report.