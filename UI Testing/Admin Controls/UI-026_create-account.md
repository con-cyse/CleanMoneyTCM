# TC-ADM-003: Create user account

Summary: Super-admin can provision CLARO users

Preconditions:

- Super-admin is logged in.
- Target campus or faculty assignment exists.
- Test email is not already registered.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Admin Controls. | Account monitoring card is visible. |
| 2 | Open Add Account dialog. | Account creation form appears. |
| 3 | Enter valid email, username, role, and organization assignment. | Form accepts values. |
| 4 | Submit the form. | New auth user and profile record are created. |
| 5 | Log in using the new account. | New user can access only the assigned organization scope. |

Post-conditions:

- New user can access only the assigned organization scope.