# UI-017: Handle missing public report

Summary: Public viewer handles unavailable reports clearly

Preconditions:

- At least one campus/faculty/semester combination has no published report.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open the public home page. | Public page loads successfully. |
| 2 | Select a campus, faculty, and semester combination with no report. | Application sends a public report lookup request. |
| 3 | Observe the PDF viewer title and content area. | Title changes to `No report found` and the viewer shows an empty-state message. |
| 4 | Confirm download controls. | Download link is not displayed for a missing report. |

Post-conditions:

- Download link is not displayed for a missing report.