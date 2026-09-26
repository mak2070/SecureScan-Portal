# 2-Minute Demo Script

## 0:00–0:20 — Problem

“Employees handle many files every day. A dangerous attachment can be shared before IT Security has a chance to review it.”

## 0:20–0:40 — Solution

“SecureScan Portal is a bilingual file-intake and threat-triage prototype. It detects risk indicators before a file is shared, gives a clear response action, and records the decision.”

## 0:40–1:15 — Run the demo

1. Open the live portal.
2. Click **Run sample incident**.
3. Point out the three synthetic results:
   - A normal PDF — Low risk.
   - A macro-enabled invoice — Medium risk.
   - A disguised executable with a double extension — High risk.
4. Explain that the indicators are visible, so the result is explainable.

## 1:15–1:40 — Containment

1. Click **Quarantine high-risk**.
2. Show the status changing to **Quarantined**.
3. Show the incident ledger recording both the scan and containment action.

## 1:40–2:00 — Impact and future

“Today the prototype works locally and never executes files. In production, it can connect to OneDrive and SharePoint through approved Microsoft Graph access, automatically triage new files, and alert security teams through Teams or a SIEM.”

## Final line

“SecureScan turns an unclear file decision into a consistent security workflow: Detect, Classify, Contain, and Record.”
