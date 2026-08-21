# CycleFuel FHA/RED-S Recovery Support PoC

An English, Chinese, and Swedish self-registration PoC for evidence-grounded daily recovery support.

- `index.html` is the participant experience. One shared test link allows approved testers to create a username and password. Login sessions are stored only on that device, and each account reads and writes only its own records.
- `admin.html` is the researcher experience. It accepts a separate administrator credential, displays participant accounts and all pseudonymous records, and reveals the shared registration link for private distribution.
- Passwords are never stored in this repository or sent to GitHub. The local backend stores only salted scrypt password hashes in the researcher's Personal OneDrive.
- No OneDrive credential, API token, participant record, or administrator secret belongs in this repository.

This prototype is educational only. It is not a diagnostic tool, medical device, treatment service, or emergency monitor. Use synthetic test data until consent, retention, deletion, incident-response, and security controls are reviewed.
