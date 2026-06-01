# TC-AUTH-005: Prevent logged-in user from returning to login page

Summary: Authenticated sessions route away from login

Preconditions:

- User is logged in.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Navigate directly to `/login`. | Middleware detects authenticated user. |
| 2 | Observe navigation result. | User is redirected away from the login page. |

Post-conditions:

- User is redirected away from the login page.