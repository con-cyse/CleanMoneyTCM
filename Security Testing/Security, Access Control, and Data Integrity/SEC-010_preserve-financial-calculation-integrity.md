# TC-SEC-005: Preserve financial calculation integrity

Summary: Generated reports and balances must match ledger entries

Preconditions:

- Test ledger contains known income and expense entries with controlled amounts.
- Balance row contains known cash and collectible values.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Dashboard and record displayed totals. | Balance cards show computed totals. |
| 2 | Generate report preview. | Report calculates from the same ledger and balance data. |
| 3 | Compare report values with manually computed expected values. | Values match exactly, including subtotals and amount-in-words fields. |
| 4 | Add another valid entry and regenerate preview. | Updated totals include the new entry once and only once. |

Post-conditions:

- Updated totals include the new entry once and only once.