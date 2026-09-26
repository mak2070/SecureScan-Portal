# SecureScan Portal

**Track:** Cyber Defense & Threat Response  
**One-line pitch:** A bilingual file-intake prototype that helps employees identify risky files before sharing them, contain high-risk items, and export an audit record.

## Live demo

[Open SecureScan Portal](https://mak2070.github.io/SecureScan-Portal/)

Click **Run sample incident** for an instant, safe demo with three synthetic files. No real malware is included or executed.

## What the prototype demonstrates

- Multi-file security triage in Arabic and English.
- Explainable risk indicators: executable/script formats, macro-enabled Office files, double extensions, suspicious filenames, file size, and readable-text indicators.
- Clear High / Medium / Low risk results, sorted by priority.
- A simulated **quarantine** action for high-risk files.
- An in-browser incident ledger and JSON audit-report export.
- Explicit, safe prototype scope: browser-only analysis and no file execution.

## Submission documents

- [Project overview](docs/PROJECT_OVERVIEW.md)
- [2-minute demo script](docs/DEMO_SCRIPT.md)
- [Architecture and security boundaries](docs/ARCHITECTURE.md)
- [Future OneDrive, SharePoint, and Teams integration](docs/FUTURE_INTEGRATIONS.md)
- [Test cases and expected outcomes](docs/TEST_CASES.md)
- [Dependencies and disclosure statement](docs/DISCLOSURES.md)
- [Presentation deck](SecureScan_Portal_Presentation.pptx)

## Run locally

Open `index.html` in Chrome, Edge, Firefox, or Safari. No install, account, API key, or internet connection is required.

## Scope and responsible use

SecureScan Portal is a safe hackathon prototype, **not an antivirus product**. It never executes uploaded files. Production deployment would require authenticated users, server-side file controls, a trusted malware-analysis provider, encrypted storage, tamper-resistant audit logs, and approved Microsoft Graph integration.
