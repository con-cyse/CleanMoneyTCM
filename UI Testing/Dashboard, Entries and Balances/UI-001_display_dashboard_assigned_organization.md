# UI-001: Display dashboard for assigned organization

Summary: Verify that the dashboard shows financial data only for the user's assigned organization.

Preconditions: User is authenticated and assigned to an organization/campus/faculty.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Verify that the user is logged in and opens the Dashboard page. | The dashboard page loads successfully. |
| 2 | Verify that the dashboard finishes loading. | The welcome card, balance section, expense table, and income table are displayed. |
| 3 | Verify that the visible entries are compared with the assigned organization data. | Only entries for the user's assigned campus or faculty are displayed. |

Post-conditions:

- The dashboard remains accessible for the assigned user.
- No data outside the user's assigned organization is shown.