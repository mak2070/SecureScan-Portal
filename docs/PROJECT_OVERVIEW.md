# Project Overview

## Problem

Employees often receive, upload, or share files before IT Security can review them. Dangerous file types, deceptive double extensions, macro-enabled documents, and social-engineering filenames can reach the company through everyday workflows.

## Solution

SecureScan Portal is a bilingual first-line file-intake and threat-triage prototype. It gives an employee or security analyst a simple workflow:

**Detect → Classify → Contain → Record**

1. Select one or more files.
2. Review explainable indicators and a High, Medium, or Low risk label.
3. Quarantine high-risk files in the simulated workflow.
4. Export a JSON incident record for security follow-up.

## Why it matters

- Reduces accidental sharing of suspicious files.
- Gives non-security employees a clear next action.
- Creates consistent evidence for the IT Security team.
- Supports Arabic and English users.

## What makes this safe

All prototype analysis happens locally in the browser. Files are never executed. The built-in sample incident uses synthetic metadata only.

## Current capabilities

| Capability | Status |
|---|---|
| Local multi-file selection | Demonstrated |
| Explainable triage rules | Demonstrated |
| Bilingual Arabic/English interface | Demonstrated |
| Simulated quarantine and audit ledger | Demonstrated |
| Downloadable JSON report | Demonstrated |
| OneDrive / SharePoint automatic scanning | Future integration |
| Teams / SIEM notifications | Future integration |
