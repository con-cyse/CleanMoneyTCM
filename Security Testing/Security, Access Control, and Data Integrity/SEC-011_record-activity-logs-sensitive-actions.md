# TC-SEC-006: Record activity logs for sensitive actions

Summary: Important financial and administrative actions are auditable

Preconditions:

- User is logged in.
- Activity log page is available.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Perform a sensitive action such as adding an entry, publishing a report, deleting a file, or updating balance data. | Action succeeds. |
| 2 | Open Activity Log page. | A new log entry appears near the top. |
| 3 | Review log details. | Description and timestamp accurately describe the performed action. |
| 4 | Log in as a different organization user. | The first user's organization log does not appear for the other organization. |

Post-conditions:

- The first user's organization log does not appear for the other organization.