# Dependencies and Disclosure Statement

## Project scope

SecureScan Portal is a static browser prototype created for AI Defense Lab 2026. It uses rule-based file triage. No runtime AI model or external API is used.

## Data

- The built-in incident examples are synthetic file metadata only.
- The project does not include malware, private data, confidential data, or personal datasets.
- A user-selected local file stays in the browser for the prototype workflow.

## Dependencies

- No npm packages, external APIs, hosted datasets, or paid services are required to run the portal.
- The prototype uses standard browser APIs: File, Blob, URL, and Intl.

## Pre-existing and third-party components

- The repository contains original SecureScan Portal code and documentation for this submission.
- No code from the separate MediaWeb repository is copied into this project. General ideas such as audit logging and operational workflow informed the product design only.
- Microsoft OneDrive, SharePoint, Microsoft Graph, Teams, and SIEM integrations are described as future architecture only. They are not active in the prototype.

## Security statement

- Uploaded binary files are never executed.
- High-risk quarantine is a safe simulation.
- Production use would require approved Microsoft Entra ID access, server-side controls, a trusted malware-analysis service, encrypted storage, and operational ownership.
