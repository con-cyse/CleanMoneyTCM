# UI-006: Edit entry description

Summary: Users can correct ledger entry descriptions

Preconditions:

- User is logged in.
- At least one income or expense entry exists.
- Dashboard is unlocked.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open the row action for an existing entry. | Edit action is available. |
| 2 | Choose Edit. | Edit Entry sheet opens with current values. |
| 3 | Change the description to a valid value. | New description is accepted. |
| 4 | Click `Save Changes`. | Entry row updates with the revised description. |

Post-conditions:

- Entry row updates with the revised description.