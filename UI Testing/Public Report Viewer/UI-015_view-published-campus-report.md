# TC-PUB-001: View published campus report

Summary: Public users can view published financial reports

Preconditions:

- At least one campus has a published financial report for an active semester.
- Public visitor is not logged in.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open the CLARO public home page. | Home page loads without requiring authentication. |
| 2 | Select a campus from the Campus dropdown. | Faculty dropdown becomes enabled and displays campus-only plus faculty options. |
| 3 | Select `Campus Only` in the Faculty dropdown. | Campus-only selection is accepted. |
| 4 | Select a semester and academic year with a published campus report. | Report viewer requests the matching public PDF. |
| 5 | Observe the viewer area. | The published campus report appears in the embedded PDF viewer with the correct title. |

Post-conditions:

- No user session is created.