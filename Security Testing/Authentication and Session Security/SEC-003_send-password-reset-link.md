# SEC-003: Send password reset link

Summary: Users can recover account access

Preconditions:

- User has a registered email address.
- Email delivery is configured in Supabase.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open `/login`. | Login card is visible. |
| 2 | Click `Forgot Password?`. | Forgot Password form replaces the login form. |
| 3 | Enter the registered email address. | Email field accepts the address. |
| 4 | Click `Send Reset Link`. | Button shows `Sending...` while processing. |
| 5 | Observe the success message. | User receives confirmation that a reset link was sent. |

Post-conditions:

- Reset email is sent to the registered address.