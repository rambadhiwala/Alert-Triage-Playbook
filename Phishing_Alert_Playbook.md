# Phishing Alert – Triage Playbook

## 1. Alert Overview
Triggered by email security gateway or user report indicating potential phishing.

## 2. Triage Flow
1. Validate alert source
2. Identify sender & recipient
3. Analyze email content
4. Inspect URLs and attachments
5. Check user interaction

## 3. Evidence Checklist
- Email headers
- Sender domain reputation
- URL reputation (VirusTotal, internal TI)
- Attachment hash
- User click/download logs

## 4. Escalation Criteria
- Credential submission confirmed
- Malicious attachment executed
- Multiple users targeted

## 5. Containment Actions
- Quarantine email
- Reset user credentials
- Block sender/domain/URL
- Force endpoint scan

## 6. Notes
Document IOCs and update phishing detection rules if needed.
