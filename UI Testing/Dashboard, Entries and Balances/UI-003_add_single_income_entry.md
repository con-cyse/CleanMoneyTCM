# UI-003: Add single income entry

Summary: Users can record income transactions

Preconditions:

- User is logged in.
- Initial balance row exists.
- Report is not published and semester is not ended.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Click `Add Entry` from the dashboard welcome card. | Add Entry sheet opens. |
| 2 | Select category `income`. | Income descriptions become available and income control number is shown. |
| 3 | Fill description, date, unit price, and quantity with valid values. | Total amount is calculated from unit price and quantity. |
| 4 | Click `Save`. | Entry is saved and sheet closes. |
| 5 | Check the Income table and balance cards. | New income entry appears and balances refresh. |

Post-conditions:

- New income entry appears and balances refresh.