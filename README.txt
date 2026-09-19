OptiMax-i Troubleshooter v2

Mobile-first PWA. Search works offline after first load.
faults.json contains manual-backed high-priority records from the supplied manual set.
No API keys are stored in the client.

Deployment to GitHub Pages:
Upload all files/folders in this package to the repository root, then enable GitHub Pages for the main branch/root.

Important coverage limitation:
The supplied Wiring and Electronic Control PDF is only the first 150 PDF pages (printed manual continues beyond it).
The supplied Part 2 PDF contains the Troubleshooting manual only through its printed page 60/106.
Therefore this build must not be represented as the complete Picanol fault catalogue.

Photo diagnosis:
UI is included. Production vision requires a protected server-side endpoint. The backend should read the displayed code/message, exact-match faults.json first, and only then use AI/web suggestions, clearly labelled separately.
