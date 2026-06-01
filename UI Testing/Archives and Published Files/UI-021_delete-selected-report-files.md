# TC-ARC-003: Delete selected report files

Summary: Users can remove obsolete published files

Preconditions:

- User is logged in.
- At least one disposable test report file exists.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Reports page. | Test file is visible. |
| 2 | Enable select mode and select the test file. | Selected row is visually marked. |
| 3 | Delete selected file. | Confirmation or delete action completes. |
| 4 | Refresh Reports page. | Deleted file no longer appears and storage object is removed. |

Post-conditions:

- Deleted file no longer appears and storage object is removed.