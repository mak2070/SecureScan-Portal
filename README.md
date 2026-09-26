# SecureScan Portal

**Track:** Cyber Defense & Threat Response  
**Pitch:** A bilingual company portal that lets employees submit many files for a fast, explainable risk triage before sharing or opening them.

## What the demo does

- Selects multiple files in one action.
- Scores risks from file name, type, size, double extensions, macro-enabled Office formats, and readable text indicators.
- Sorts results by high, medium, and low risk.
- Gives an immediate action for each file.
- Exports the results as a JSON incident report.
- Switches fully between Arabic (RTL) and English.

## Run it

Open `index.html` in Chrome, Edge, Firefox, or Safari. No installation, internet connection, account, or API key is required.

## Demo flow - 2 minutes

1. State the problem: employees can upload or forward dangerous files accidentally.
2. Select several files; include a `.docm`, `.js`, or a filename with `invoice` for the demo.
3. Click **Scan selected files**.
4. Show that high-risk files go to the top with a containment action.
5. Click **Download report** and switch the portal to Arabic.
6. Close with the impact: consistent first-line triage and clear evidence for the security team.

## Security and scope

This is a safe hackathon prototype. It never executes uploaded files and performs analysis in the browser only. It is **not an antivirus product** and should not be used as the only production security control.

For production, integrate a trusted malware scanning service or sandbox, enforce file-size/type policies on the server, authenticate users, encrypt stored data, keep tamper-resistant audit logs, and route confirmed alerts to a SIEM/SOAR platform.
