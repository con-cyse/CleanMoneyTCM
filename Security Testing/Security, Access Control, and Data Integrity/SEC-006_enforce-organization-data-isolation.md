# TC-SEC-001: Enforce organization data isolation

Summary: Users must only access data for their assigned campus or faculty

Preconditions:

- User A belongs to Faculty A.
- User B belongs to Faculty B or Campus B.
- Both organizations have reports, archives, and ledger entries.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Log in as User A. | Session starts successfully. |
| 2 | Open Dashboard, Reports, Archives, and Activity Log. | Only Faculty A or assigned organization data appears. |
| 3 | Attempt to manually request another organization's file or record through visible URL parameters if available. | Application does not expose unauthorized data. |

Post-conditions:

- Application does not expose unauthorized data.