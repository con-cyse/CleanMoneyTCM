# TC-SEC-002: Protect public PDF endpoint from broad data exposure

Summary: Public endpoint returns only explicitly published report PDFs

Preconditions:

- Published and unpublished reports exist.
- Public visitor is not logged in.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Request public PDF with valid campus/faculty/semester for a published report. | Endpoint returns a signed URL for that report only. |
| 2 | Request public PDF with filters for an unpublished or deleted report. | Endpoint returns not found or no report response. |
| 3 | Try adding unrelated query parameters. | Endpoint ignores unauthorized parameters and does not reveal other records. |

Post-conditions:

- Endpoint ignores unauthorized parameters and does not reveal other records.