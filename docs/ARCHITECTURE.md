# Architecture and Security Boundaries

## Prototype architecture

```mermaid
flowchart LR
  U[Employee or analyst] --> P[SecureScan browser portal]
  P --> R[Local triage rules]
  R --> Q[Priority results]
  Q --> C[Simulated quarantine]
  Q --> A[JSON audit report]
```

## Security boundaries

- The prototype reads selected file metadata and readable text only where the browser permits it.
- Binary files are **not executed**.
- Files are not uploaded to a backend.
- The audit report is downloaded by the user as JSON.
- The prototype does not claim malware detection or real-time cloud monitoring.

## Production target architecture

```mermaid
flowchart LR
  O[OneDrive / SharePoint] --> G[Microsoft Graph webhook]
  G --> S[Secure server-side scanning service]
  S --> M[Approved malware sandbox]
  S --> D[Encrypted audit store]
  S --> T[Teams / SIEM alert]
```

## Production controls required

- Microsoft Entra ID authentication and role-based access.
- Least-privilege Microsoft Graph permissions.
- Server-side file-size and file-type limits.
- Encryption in transit and at rest.
- Tamper-resistant audit logs.
- A trusted malware-analysis or sandbox provider.
- Incident-response ownership and retention rules.
