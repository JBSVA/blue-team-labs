# Phishing Investigation #1

## Email Overview
- Reported by: User
- Date received: Unknown
- Subject: New Voice Message
- Sender address: Unknown (spoofed voicemail notification)

## Initial Assessment
This email appears suspicious because it claims to be a new voicemail from an unknown number and includes an attachment that prompts the user to download a file. The Office 365 logo is used to make the email look legitimate, and the attachment ultimately leads to a page disguised as an Outlook login, which is a common phishing tactic to capture credentials.

## Header Analysis
- SPF result: Unknown / not provided in sample
- DKIM result: Unknown / not provided in sample
- DMARC result: Unknown / not provided in sample
- Sending IP: Unknown / spoofed

## URL & Attachment Analysis
| Indicator | Type | Reputation |
|-----------|------|------------|
| Attachment prompting download of voice message | File | Malicious (leads to credential phishing page) |
| Page disguised as Outlook login | URL | Malicious (credential harvesting) |

## Threat Intelligence Findings
Summarize results from VirusTotal, AbuseIPDB, MXToolbox, or URLscan.

## Verdict
Malicious / Benign / Suspicious

## Recommended Response Actions
- User notification:
- Blocking actions:
- Escalation required:
