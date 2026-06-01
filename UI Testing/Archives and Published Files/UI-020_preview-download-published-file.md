# TC-ARC-002: Preview and download published file

Summary: Users can inspect and download generated documents

Preconditions:

- User is logged in.
- Reports page contains at least one PDF or image file.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Reports page. | File table displays available files. |
| 2 | Open a file preview. | Viewer dialog displays the PDF or image using a signed URL. |
| 3 | Click download. | File downloads or opens in a new browser tab. |

Post-conditions:

- File downloads or opens in a new browser tab.