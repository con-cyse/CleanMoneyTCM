# TC-AUTH-001: Login with valid email and password

Summary: Authorized users can access protected CLARO pages

Preconditions:

- A verified user account exists in Supabase Auth.
- Matching user profile exists in the `users` table with campus or faculty assignment.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Navigate to `/login`. | Login form displays username/email and password fields. |
| 2 | Enter a valid email and password. | Input is accepted without validation errors. |
| 3 | Click `Login`. | Button shows a loading state while authentication is in progress. |
| 4 | Wait for completion. | User is redirected to the appropriate authenticated area. |
| 5 | Open Dashboard from the sidebar. | Dashboard data for the user's campus or faculty is displayed. |

Post-conditions:

- Dashboard data for the user's campus or faculty is displayed.