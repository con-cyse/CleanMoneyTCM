# TC-ADM-002: Deny admin controls to non-super-admin

Summary: Admin controls must be role restricted

Preconditions:

- User is logged in as regular faculty or campus user.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Navigate directly to the admin controls route. | Middleware or route guard evaluates user role. |
| 2 | Observe navigation. | User is redirected away from admin controls. |
| 3 | Confirm page contents. | Semester/account management controls are not exposed. |

Post-conditions:

- Semester/account management controls are not exposed.