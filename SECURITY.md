# Security design

## Safe-by-default demo choices

- Uploaded files are never executed.
- Analysis happens only in the user browser.
- No file, credential, or scan result is sent to a remote service.
- Text content is limited to 250 KB during the demo to avoid browser stalls.
- The downloaded report contains only the local scan results.

## Production controls required

1. Server-side authentication and role-based access control.
2. Malware scanning and sandboxing in an isolated service.
3. Private encrypted storage with retention rules.
4. Immutable audit events for uploads, scans, decisions, and exports.
5. Rate limits, file-size limits, allow/deny type policies, and content-disposition downloads.
6. Human review before destructive actions.
