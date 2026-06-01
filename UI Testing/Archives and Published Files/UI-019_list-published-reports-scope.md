# TC-ARC-001: List published reports for user scope

Summary: Users can browse reports for their organization only

Preconditions:

- User is logged in.
- At least two reports exist across different organizations.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Reports page. | File table loads after user scope is resolved. |
| 2 | Review listed files. | Only files matching the user's campus or faculty are shown. |
| 3 | Verify ordering. | Most recently published files appear first. |

Post-conditions:

- Most recently published files appear first.