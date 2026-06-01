# TC-AUTH-002: Reject invalid login credentials

Summary: Invalid credentials must not create sessions

Preconditions:

- Login page is available.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Navigate to `/login`. | Login form displays. |
| 2 | Enter an unknown email or incorrect password. | Fields accept the values. |
| 3 | Click `Login`. | Authentication request is submitted. |
| 4 | Observe the page. | Error message is shown and user remains on the login page. |
| 5 | Attempt to open `/dashboard`. | User is redirected back to `/login`. |

Post-conditions:

- User is redirected back to `/login`.