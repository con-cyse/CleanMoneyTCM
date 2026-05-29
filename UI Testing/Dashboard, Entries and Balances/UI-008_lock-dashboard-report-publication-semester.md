# UI-008: Lock dashboard after report publication or semester end

Summary: Published or closed financial records cannot be modified casually

Preconditions:

- User is logged in.
- Organization has a published report or ended semester.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Dashboard. | Existing entries and balances are visible. |
| 2 | Inspect add, edit, delete, and balance update controls. | Mutation controls are disabled or hidden. |
| 3 | Attempt direct UI mutation if any control is visible. | Application prevents the change. |

Post-conditions:

- Application prevents the change.