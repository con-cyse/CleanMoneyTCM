# TC-ARC-005: Delete archive folder

Summary: Users can manage obsolete receipt archive folders

Preconditions:

- User is logged in.
- A disposable receipt archive folder exists.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Archives page. | Folder is visible in the table. |
| 2 | Select the folder. | Folder row is selected. |
| 3 | Delete the selected folder. | Folder row is removed. |
| 4 | Refresh Archives page. | Folder remains deleted. |

Post-conditions:

- Folder remains deleted.