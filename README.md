# CycleFuel FHA/RED-S Recovery Support PoC

An English, Chinese, and Swedish private-invitation PoC for evidence-grounded daily recovery support.

- `index.html` is the participant experience. It accepts a participant-specific API address and token from the URL fragment, stores them only on that device, clears the fragment, and reads/writes only that participant's records.
- `admin.html` is the researcher experience. It accepts a separate administrator credential, displays all pseudonymous records, and creates participant invitation links.
- No OneDrive credential, API token, participant record, or administrator secret belongs in this repository.

This prototype is educational only. It is not a diagnostic tool, medical device, treatment service, or emergency monitor. Use synthetic test data until consent, retention, deletion, incident-response, and security controls are reviewed.
