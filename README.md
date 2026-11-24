# St Columb's College — school platform demo
Version 5 is the initial canonical frontend baseline. This is an independent demonstration, not an official college service.
## Run
Open `index.html` locally in a browser. Start at role selection, choose a demo account. Spanish study and local M1 question generation work offline. Staff workflows are interface previews. See AGENTS.md for established product requirements.
## Architecture and next steps
The frontend is currently self-contained HTML/CSS/JavaScript. A Python Maths backend and private curriculum reference package were developed separately in the Version 5 ZIP supplied in the original chat. Live AI requires a server and configured API key; no live AI calls have been validated. The repository must not contain secrets or restricted source materials. Until backend integration is verified, use the offline demo only.
## Workflow
This repository is the source of truth for future changes. Read latest main, use a branch for substantial features, test, commit, and merge reviewed changes. GitHub is source control, not live hosting. Authentication, role permissions, persistent server-side storage, teacher review and safeguarding are required before use with real pupils.
