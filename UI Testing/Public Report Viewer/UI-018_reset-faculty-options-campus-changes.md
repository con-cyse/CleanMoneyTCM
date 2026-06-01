# TC-PUB-004: Reset faculty options when campus changes

Summary: Public report filters remain consistent

Preconditions:

- Two campuses exist and each has different faculties.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open the public home page. | Dropdown filters are visible. |
| 2 | Select Campus A and one of its faculties. | Faculty selection is accepted. |
| 3 | Change the campus to Campus B. | Faculty selection is cleared. |
| 4 | Open the Faculty dropdown. | Only Campus B faculty options and Campus B campus-only option are shown. |

Post-conditions:

- Only Campus B faculty options and Campus B campus-only option are shown.