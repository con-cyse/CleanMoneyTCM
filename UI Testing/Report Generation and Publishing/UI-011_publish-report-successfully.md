# UI-011: Publish report successfully

Summary: Users can publish official reports to storage and database records

Preconditions:

- User is logged in.
- Publish form has complete valid report data.
- Target Supabase storage bucket is available.

Scenario 1

| # | Step | Expected Behavior |
| --- | --- | --- |
| 1 | Open Publish dialog. | Dialog displays report form and publish controls. |
| 2 | Fill or auto-generate required report fields. | Form becomes ready for publishing. |
| 3 | Click Publish. | PDF is generated and uploaded to the correct bucket. |
| 4 | Wait for completion. | Success feedback is shown and dashboard recognizes the report as published. |
| 5 | Open Reports page. | Newly published report appears at the top of the file list. |

Post-conditions:

- A report row exists and a corresponding PDF exists in storage.