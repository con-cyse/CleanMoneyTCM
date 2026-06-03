# UI-022: Display archive files and receipt folders

Summary: Users can browse archived reports and receipt folders

Preconditions:

- User is logged in.
- Archive files and receipt archive folders exist for the user's organization.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Archives page. | Combined archive list loads. |
| 2 | Review displayed rows. | Archive files and folders appear in one sorted list. |
| 3 | Click a folder row. | Browser navigates to that folder's archive detail page. |

Post-conditions:

- Browser navigates to that folder's archive detail page.