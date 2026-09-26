# Future Integrations

## OneDrive and SharePoint

The live prototype currently uses local browser upload only.

For production, SecureScan can be connected to OneDrive and SharePoint through Microsoft Graph:

1. Register the application in Microsoft Entra ID.
2. Obtain administrator-approved, least-privilege permissions.
3. Subscribe to changes in approved folders or document libraries.
4. Send new or modified files to a secure server-side triage service.
5. Place high-risk files in a quarantine location and create an audit event.

## Security notifications

High-risk findings can be routed to:

- Microsoft Teams for rapid analyst notification.
- Microsoft Sentinel or another SIEM for correlation and incident response.
- A ticketing system for ownership and closure tracking.

## Important boundary

These integrations are future scope and require a company Microsoft 365 tenant, Entra ID configuration, security review, and administrator consent. They are intentionally not represented as active in the current demo.
