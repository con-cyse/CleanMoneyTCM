# TC-SEC-003: Prevent storage access after signed URL expiry

Summary: Document URLs should be time-limited

Preconditions:

- User can generate a signed URL for a report or archive.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Reports or Archives and preview a file. | File loads through a signed URL. |
| 2 | Copy the signed URL. | URL contains time-limited access parameters. |
| 3 | Wait past configured expiry. | Previously copied URL no longer grants access. |
| 4 | Refresh the application page. | Application generates a fresh signed URL for authorized users. |

Post-conditions:

- Application generates a fresh signed URL for authorized users.