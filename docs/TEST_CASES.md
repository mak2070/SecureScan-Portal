# Test Cases

Use **Run sample incident** to show the first three cases safely.

| Case | Input | Expected result |
|---|---|---|
| Safe document | `Q3_Finance_Summary.pdf` | Low risk; no urgent action |
| Macro document | `Invoice_Review.docm` | Medium risk; isolate and review |
| Deceptive executable | `Payment_Update.pdf.exe` | High risk; quarantine and alert |
| Script file | Any `.js`, `.ps1`, or `.bat` file | High risk |
| Suspicious text | Text file containing `powershell` or `cmd.exe` | Medium or High indicator shown |
| Report export | Click **Download report** after a scan | JSON file downloads with results and ledger |
| Language | Click **العربية** | Portal switches to Arabic and RTL layout |

## Acceptance checks

- The page works without a backend or account.
- The sample incident completes without loading unsafe code.
- High-risk quarantine updates the status and the incident ledger.
- The report contains the scan result and recorded actions.
