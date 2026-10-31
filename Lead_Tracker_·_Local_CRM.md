# Lead Tracker · Local CRM

A standalone lead-tracking web app built with HTML, CSS, and vanilla JavaScript. It runs directly in Chrome and can be published with GitHub Pages.

## Features

- Add, edit, delete, and update lead stages
- Search by name, business, phone, or notes
- Filter by stage or follow-up status
- Sort by follow-up priority, newest, value, or name
- Dashboard totals for leads, follow-ups, open pipeline, and won value
- Follow-up date highlighting for today and overdue leads
- WhatsApp shortcut for phone numbers
- CSV export and CSV import for backups/restoration
- Manual light/dark mode toggle
- Responsive layout for desktop and mobile
- Local browser storage; no server or account required

## Run locally

Open `lead-tracker-v2.html` in Chrome. To use the same saved data consistently, keep using the same browser and URL. Export a CSV backup regularly.

## Publish with GitHub Pages

1. Rename `lead-tracker-v2.html` to `index.html` if you want it to be the repository homepage.
2. Commit and push the file to GitHub.
3. In the repository, open **Settings → Pages**.
4. Choose the branch and root folder, then save.
5. Open the generated `github.io` URL in Chrome and create a desktop shortcut.

## Important limitation

This version is intentionally local-first. Leads are stored in the browser's `localStorage`, so they are not shared between devices or users. A future backend version would add authentication, a database, validation on the server, and synchronization across devices. Do not store sensitive personal information in this demo without adding appropriate security controls.
