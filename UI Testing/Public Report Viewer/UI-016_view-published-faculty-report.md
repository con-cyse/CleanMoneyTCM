# UI-016: View published faculty report

Summary: Public users can filter reports by campus, faculty, and semester

Preconditions:

- A faculty has a published financial report for a known semester.
- Public visitor is not logged in.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open the public home page. | Public page loads successfully. |
| 2 | Select the faculty's campus. | Faculty options for the selected campus are loaded. |
| 3 | Select the target faculty. | Selected faculty remains visible in the dropdown. |
| 4 | Select the semester of the published report. | Matching faculty report is fetched. |
| 5 | Click the download icon. | Browser starts downloading or opening the same signed PDF URL. |

Post-conditions:

- Report remains published and available.