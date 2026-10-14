# Maa Santé — demonstration prototype

Maternal appointment follow-up tool proposed by CEFEG SARL, Guinea.

## Run
Open index.html in a modern browser. No installation or build is required. French text-to-speech depends on browser and installed voices.

## Implemented
Fictional records; antenatal/postnatal categories; appointment scheduling and rescheduling; completion tracking; overdue lists; search; simulated reminders; French browser speech synthesis; responsive interface.

## Test walkthrough
1. Open Femmes suivies and create a fictional record.
2. Open its details and change the appointment date.
3. Mark the consultation completed, then return it to pending.
4. Search for the fictional name.
5. Simulate a reminder: no SMS is sent.
6. Reload: browser-local changes should remain where local storage is supported.
7. Reset the demo to restore three fictional records.

## Current limitations
No clinical field trial, no implemented AI, no real messaging, no shared database, no clinical decision support, no production authentication or consent management. Automated software checks have covered record creation, output escaping, completion, rescheduling and search; mobile browser usability remains to be assessed.

## Privacy
Use fictional data only. Records stay in this browser through localStorage. Do not enter patient data. Storage is not suitable for clinical production. Open-source publication of code does not entail publication of any patient information.

## Planned pilot (not implemented)
50 pregnant women, one facility, 45 days, subject to partnership and privacy safeguards. Planned secure storage, role-based access, communication preferences, consent, validated language content and operational analytics.

## Evaluation access
The source must be published to a repository accessible to UNICEF reviewers. The privately hosted demo alone does not provide evaluator access. This archive is prepared for repository publication; publication has now been completed in this repository.

## Licence
No open-source licence has been applied yet. CEFEG should confirm ownership and select an appropriate licence before publication. The application states willingness to open source.
