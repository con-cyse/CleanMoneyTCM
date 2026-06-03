# SEC-004: Redirect unauthenticated protected-route access

Summary: Protected routes require authentication

Preconditions:

- Browser has no active CLARO session.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open a protected route such as `/dashboard`, `/reports`, `/archives`, or `/settings`. | Middleware checks the current session. |
| 2 | Observe navigation. | Browser is redirected to `/login`. |
| 3 | Use browser Back button. | Protected content is not displayed. |

Post-conditions:

- Protected content is not displayed.